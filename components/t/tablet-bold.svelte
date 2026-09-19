<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/us361hl1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="us361hl1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:tablet-bold" {...props}></Icon>
