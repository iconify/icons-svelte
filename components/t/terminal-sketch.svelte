<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/o4qq2hmsv.css';
import '../../css/r/re7id0y1c.css';
import '../../css/s/sx20ad8rv.css';
import '../../css/u/unn-0zbjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="o4qq2hmsv"/><path class="re7id0y1c wm-a"/><path class="sx20ad8rv wm-k"/><path class="unn-0zbjb wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:terminal-sketch" {...props}></Icon>
