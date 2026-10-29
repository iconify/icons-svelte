<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/w51c1j92o.css';
import '../../css/f/f460cp0ja.css';
import '../../css/o/o21xwxcop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="w51c1j92o wm-a"/><path class="f460cp0ja wm-k"/><path class="o21xwxcop wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:tv-sketch" {...props}></Icon>
