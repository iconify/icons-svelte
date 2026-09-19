<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lovk9xqtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="lovk9xqtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:volume" {...props}></Icon>
