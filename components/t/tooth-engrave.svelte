<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/wo03t_npi.css';
import '../../css/o/ozwb22glz.css';
import '../../css/w/wjf1ikbgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wo03t_npi"/><path class="ozwb22glz wm-shadow"/><path class="wjf1ikbgx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:tooth-engrave" {...props}></Icon>
