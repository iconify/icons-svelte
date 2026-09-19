<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6d7x4bpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="m6d7x4bpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:scissors-open-1" {...props}></Icon>
