<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lafhkbbho.css';
import '../../css/w/wqa4-ac6s.css';
import '../../css/w/w4vxnac6h.css';
import '../../css/p/pkx569b0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="lafhkbbho"/><path class="wqa4-ac6s"/><path class="w4vxnac6h"/><path class="pkx569b0p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:stop-circle-duo" {...props}></Icon>
