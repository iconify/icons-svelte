<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/baw6f0ben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="baw6f0ben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:square-facebook" {...props}></Icon>
