<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_ghm2b4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="c_ghm2b4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:volume-duo" {...props}></Icon>
