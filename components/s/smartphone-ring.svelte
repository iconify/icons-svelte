<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wv9mw16ld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":480};
const content = `<path class="wv9mw16ld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:smartphone-ring" {...props}></Icon>
