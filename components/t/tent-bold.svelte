<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-yy--nmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="j-yy--nmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:tent-bold" {...props}></Icon>
