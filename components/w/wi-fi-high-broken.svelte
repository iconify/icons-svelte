<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/z/zj2p4py0y.css';
import '../../css/a/af3t0nyrd.css';
import '../../css/v/vn7srixjk.css';
import '../../css/p/pn5tqtb4p.css';
import '../../css/i/iejxo-b0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="zj2p4py0y"/><path class="af3t0nyrd"/><path class="vn7srixjk"/><path class="pn5tqtb4p"/><path class="iejxo-b0t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:wi-fi-high-broken" {...props}></Icon>
