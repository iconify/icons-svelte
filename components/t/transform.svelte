<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/b/bg65hobfr.css';
import '../../css/d/dq_8uac5l.css';
import '../../css/h/h77qjobjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><circle class="bg65hobfr"/><circle class="dq_8uac5l"/><path class="h77qjobjk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:transform" {...props}></Icon>
