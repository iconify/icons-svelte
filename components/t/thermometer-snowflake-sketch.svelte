<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/cmyeelv4u.css';
import '../../css/o/ohsupcbxt.css';
import '../../css/i/inidtdb2d.css';
import '../../css/a/aulea8_ox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="cmyeelv4u"/><path class="ohsupcbxt wm-a"/><path class="inidtdb2d wm-k"/><path class="aulea8_ox wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:thermometer-snowflake-sketch" {...props}></Icon>
