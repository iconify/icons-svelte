<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/jzynihb1h.css';
import '../../css/x/xruxbuhom.css';
import '../../css/w/wjgsuii2v.css';
import '../../css/y/yis2aibtu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="jzynihb1h wm-k"/><path class="wm-a xruxbuhom"/><path class="wjgsuii2v wm-k"/><path class="wm-a yis2aibtu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:scan-barcode-sketch" {...props}></Icon>
