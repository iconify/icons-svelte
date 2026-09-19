<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpmh16bpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="wpmh16bpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:wikipedia" {...props}></Icon>
