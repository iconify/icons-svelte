<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldvkl4b8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ldvkl4b8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:wifi-100" {...props}></Icon>
