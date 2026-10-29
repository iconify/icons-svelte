<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/z/z6c_4cipf.css';
import '../../css/t/tfl1-h3qx.css';
import '../../css/m/mhlqgvb8s.css';
import '../../css/i/ipkd9vbgw.css';
import '../../css/h/hchqqbcqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k z6c_4cipf"/><path class="tfl1-h3qx wm-a"/><path class="mhlqgvb8s wm-shadow"/><path class="ipkd9vbgw wm-k"/><path class="hchqqbcqj wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:thermometer-snowflake-engrave" {...props}></Icon>
