<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/uj3lqpbzs.css';
import '../../css/p/pmtadbchy.css';
import '../../css/v/vnwlw3via.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="uj3lqpbzs"/><path class="pmtadbchy wm-shadow"/><path class="vnwlw3via"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:wrench-engrave" {...props}></Icon>
