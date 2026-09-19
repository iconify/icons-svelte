<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0ovf5b2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="p0ovf5b2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:v" {...props}></Icon>
