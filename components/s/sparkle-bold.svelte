<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jut4up8jl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="jut4up8jl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:sparkle-bold" {...props}></Icon>
