<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/x/xdfr29bzc.css';
import '../../css/c/c12_yhz0x.css';
import '../../css/q/qyd-9_-em.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="xdfr29bzc"/><rect class="c12_yhz0x"/><path class="qyd-9_-em"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:subtract-selection-one" {...props}></Icon>
