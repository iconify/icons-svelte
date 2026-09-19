<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/az0bjmbtg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="az0bjmbtg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:seven-bold" {...props}></Icon>
