<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q221gvjez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="q221gvjez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:sparkles-1-bold" {...props}></Icon>
