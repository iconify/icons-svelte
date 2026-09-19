<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4wc7m-ir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="x4wc7m-ir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:volume-2" {...props}></Icon>
