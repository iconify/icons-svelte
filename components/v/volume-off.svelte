<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mz6g2ynyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":512};
const content = `<path class="mz6g2ynyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:volume-off" {...props}></Icon>
