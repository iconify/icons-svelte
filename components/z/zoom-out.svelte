<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0alxpbib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="v0alxpbib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:zoom-out" {...props}></Icon>
