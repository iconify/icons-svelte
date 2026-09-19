<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wob_gub2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="wob_gub2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:zero-bold" {...props}></Icon>
