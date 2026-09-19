<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/l2rvtoxlz.css';
import '../../css/t/t43vemb6k.css';
import '../../css/u/u4agv6btr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="l2rvtoxlz"/><path class="t43vemb6k"/><path class="u4agv6btr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:solar-power" {...props}></Icon>
