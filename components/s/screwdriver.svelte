<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/i_rn3obdo.css';
import '../../css/m/m4i19tyoh.css';
import '../../css/x/x94spybsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="i_rn3obdo"/><path class="m4i19tyoh"/><path class="x94spybsx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:screwdriver" {...props}></Icon>
