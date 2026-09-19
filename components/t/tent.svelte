<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrl37cc2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="vrl37cc2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:tent" {...props}></Icon>
