<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxkgd3qty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vxkgd3qty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:svg-document" {...props}></Icon>
