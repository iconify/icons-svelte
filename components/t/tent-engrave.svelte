<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/x4iq_5ybs.css';
import '../../css/p/ppi5x7mln.css';
import '../../css/q/qlf4-g8mc.css';
import '../../css/x/xlau4cdnj.css';
import '../../css/k/koqkggbqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k x4iq_5ybs"/><path class="ppi5x7mln wm-a"/><path class="qlf4-g8mc wm-shadow"/><path class="wm-k xlau4cdnj"/><path class="koqkggbqh wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:tent-engrave" {...props}></Icon>
