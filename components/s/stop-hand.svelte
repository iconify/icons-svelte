<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fl7ncac3m.css';
import '../../css/f/f8cw07bfb.css';
import '../../css/s/sgba66btq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="fl7ncac3m"/><path class="f8cw07bfb"/><path clip-rule="evenodd" class="sgba66btq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:stop-hand" {...props}></Icon>
