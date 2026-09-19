<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fz8ezkb8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="fz8ezkb8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:search-tint-bold" {...props}></Icon>
