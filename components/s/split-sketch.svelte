<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/v55c813ts.css';
import '../../css/i/i9wr98bya.css';
import '../../css/p/pi715z2hw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="v55c813ts wm-k"/><path class="i9wr98bya wm-k"/><path class="pi715z2hw wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:split-sketch" {...props}></Icon>
