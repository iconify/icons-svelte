<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl_jpu8fi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yl_jpu8fi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:wifi-signal-4" {...props}></Icon>
