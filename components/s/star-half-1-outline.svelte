<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0xyldb6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="v0xyldb6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:star-half-1-outline" {...props}></Icon>
