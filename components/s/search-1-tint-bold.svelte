<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuzrg11of.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="cuzrg11of"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:search-1-tint-bold" {...props}></Icon>
