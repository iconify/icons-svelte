<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bv45cu70d.css';
import '../../css/m/mgrc7zb-j.css';
import '../../css/x/x51wmgiym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="bv45cu70d"/><path clip-rule="evenodd" class="mgrc7zb-j"/><path class="x51wmgiym"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:sofa" {...props}></Icon>
