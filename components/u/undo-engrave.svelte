<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/ajbqyxbct.css';
import '../../css/v/vt6-ivbtd.css';
import '../../css/y/y47r9-bnz.css';
import '../../css/v/vwp9wpqdw.css';
import '../../css/r/r1uvmmr9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ajbqyxbct wm-k"/><path class="vt6-ivbtd wm-a"/><path class="wm-shadow y47r9-bnz"/><path class="vwp9wpqdw wm-k"/><path class="r1uvmmr9d wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:undo-engrave" {...props}></Icon>
