<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cg23gwpnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="cg23gwpnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:triangle-duo" {...props}></Icon>
