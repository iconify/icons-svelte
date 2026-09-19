<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/i/iporvewwo.css';
import '../../css/v/vf5jtqb5z.css';
import '../../css/e/ecam5r2nq.css';
import '../../css/z/zybhtbb_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="iporvewwo"/><path class="vf5jtqb5z"/><path class="ecam5r2nq"/><path clip-rule="evenodd" class="zybhtbb_p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:scissors-open" {...props}></Icon>
