<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/u/u7g_ur07w.css';
import '../../css/e/ebpntvbiw.css';
import '../../css/q/q_s4rbbpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="u7g_ur07w"/><path class="ebpntvbiw"/><path class="q_s4rbbpt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:user-square-alt" {...props}></Icon>
