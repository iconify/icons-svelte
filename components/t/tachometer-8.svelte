<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h7e2b6-4b.css';
import '../../css/t/t267_cb-w.css';
import '../../css/j/jmk2flbmo.css';
import '../../css/q/q63e-prrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="h7e2b6-4b"/><path class="t267_cb-w"/><path class="jmk2flbmo"/><path class="q63e-prrf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:tachometer-8" {...props}></Icon>
