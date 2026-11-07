<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/an--fmawt.css';
import '../../css/p/p2-28vwqt.css';
import '../../css/k/kdx2-qp7s.css';
import '../../css/p/pjpaztbao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="an--fmawt"/><path class="p2-28vwqt"/><path class="kdx2-qp7s"/><path class="pjpaztbao"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:watch-round-broken" {...props}></Icon>
