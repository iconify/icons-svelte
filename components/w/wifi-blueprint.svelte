<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/f/fxlwt65ty.css';
import '../../css/y/y3nvvebgo.css';
import '../../css/w/wcas29b1h.css';
import '../../css/h/hjpmvwbth.css';
import '../../css/z/z05c70bso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="fxlwt65ty wm-deco"/><path class="wm-deco y3nvvebgo"/><path class="wcas29b1h wm-deco"/><path class="hjpmvwbth"/><path class="z05c70bso"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:wifi-blueprint" {...props}></Icon>
