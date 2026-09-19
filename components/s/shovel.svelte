<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/h/hwlm2kwmc.css';
import '../../css/l/ld8emebna.css';
import '../../css/x/x83hjc4qv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="hwlm2kwmc"/><path class="ld8emebna"/><rect class="x83hjc4qv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:shovel" {...props}></Icon>
