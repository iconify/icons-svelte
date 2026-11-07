<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/kdx2-qp7s.css';
import '../../css/s/s0ay1abnm.css';
import '../../css/w/w37drss5a.css';
import '../../css/p/p2-28vwqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="kdx2-qp7s"/><path class="s0ay1abnm"/><path class="w37drss5a"/><path class="p2-28vwqt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:watch-round-linear" {...props}></Icon>
