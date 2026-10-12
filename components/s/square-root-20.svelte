<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xc5u-tbli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xc5u-tbli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:square-root-20" {...props}></Icon>
