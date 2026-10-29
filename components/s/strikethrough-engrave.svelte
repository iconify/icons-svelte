<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/wvopw9ncy.css';
import '../../css/t/two_v_bki.css';
import '../../css/q/q1-hjfupd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wvopw9ncy"/><path class="two_v_bki wm-shadow"/><path class="q1-hjfupd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:strikethrough-engrave" {...props}></Icon>
