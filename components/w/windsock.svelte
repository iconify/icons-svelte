<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3d0i0bvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="z3d0i0bvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:windsock" {...props}></Icon>
