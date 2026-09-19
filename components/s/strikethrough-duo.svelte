<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5_-s9p0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="e5_-s9p0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:strikethrough-duo" {...props}></Icon>
