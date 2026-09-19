<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebzc7_bra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ebzc7_bra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:sunrise-1" {...props}></Icon>
