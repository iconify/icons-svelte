<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/yrp8owbwe.css';
import '../../css/d/dgp6cjnjf.css';
import '../../css/m/mvz31c87g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="yrp8owbwe"/><path class="dgp6cjnjf"/><path class="mvz31c87g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:snow-bold" {...props}></Icon>
