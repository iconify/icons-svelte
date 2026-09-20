<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/qrjnaipku.css';
import '../../css/k/kknkqexjp.css';
import '../../css/m/mex7ymchk.css';
import '../../css/x/xr5b5tbwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="qrjnaipku"/><path class="kknkqexjp"/><path class="mex7ymchk"/><path class="xr5b5tbwe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-print:text-bubbles" {...props}></Icon>
