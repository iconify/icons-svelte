<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc-207mnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="lc-207mnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:square-vimeo" {...props}></Icon>
