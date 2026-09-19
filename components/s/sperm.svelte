<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/r/ree79tbzy.css';
import '../../css/s/sq_622bov.css';
import '../../css/r/rp1r7sbyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path clip-rule="evenodd" class="ree79tbzy"/><path class="sq_622bov"/><path class="rp1r7sbyy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:sperm" {...props}></Icon>
