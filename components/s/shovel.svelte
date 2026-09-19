<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ct_xoybyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ct_xoybyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:shovel" {...props}></Icon>
