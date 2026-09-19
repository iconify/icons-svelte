<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxl1ejw5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vxl1ejw5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:videocam" {...props}></Icon>
