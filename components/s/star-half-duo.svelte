<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0e5sw3yl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="u0e5sw3yl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:star-half-duo" {...props}></Icon>
