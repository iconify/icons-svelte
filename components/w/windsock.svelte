<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/ttod6dbvm.css';
import '../../css/h/hi_ztfptr.css';
import '../../css/r/rnunjybvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="ttod6dbvm"/><path class="hi_ztfptr"/><path clip-rule="evenodd" class="rnunjybvs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:windsock" {...props}></Icon>
