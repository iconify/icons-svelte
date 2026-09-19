<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/u/urpg4uckh.css';
import '../../css/u/u9mxqjotv.css';
import '../../css/d/d7_ejibjy.css';
import '../../css/m/mujnpf-ls.css';
import '../../css/j/j2lw68b4y.css';
import '../../css/m/mdrt5ab6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><circle class="urpg4uckh"/><path class="u9mxqjotv"/><circle class="d7_ejibjy"/><path class="mujnpf-ls"/><circle class="j2lw68b4y"/><path class="mdrt5ab6m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:transactions-outline" {...props}></Icon>
