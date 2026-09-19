<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/q/q9_aebbll.css';
import '../../css/x/xrrp2vbhl.css';
import '../../css/n/ndgf8g0be.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="q9_aebbll"/><circle transform="rotate(-90 13 8.944)" class="xrrp2vbhl"/><path class="ndgf8g0be"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:split-turn-down-right" {...props}></Icon>
