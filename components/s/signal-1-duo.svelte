<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_x5j7b6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="o_x5j7b6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:signal-1-duo" {...props}></Icon>
