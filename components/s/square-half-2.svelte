<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czkzp8abb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="czkzp8abb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:square-half-2" {...props}></Icon>
