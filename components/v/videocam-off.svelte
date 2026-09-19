<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ex-4i4b2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":408,"height":408};
const content = `<path class="ex-4i4b2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:videocam-off" {...props}></Icon>
