<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7_rc0b0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="e7_rc0b0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:underline-bold" {...props}></Icon>
