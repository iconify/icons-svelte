<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f83i5e07h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="f83i5e07h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:spade-duo" {...props}></Icon>
