<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/p/pj443b1og.css';
import '../../css/r/rqkm5wdvg.css';
import '../../css/r/r98xe4b5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="pj443b1og"/><path class="rqkm5wdvg"/><path class="r98xe4b5t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:snow" {...props}></Icon>
