<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/blor6etyc.css';
import '../../css/m/m49hu2bxr.css';
import '../../css/v/v1kuu0bke.css';
import '../../css/u/uq6pq445a.css';
import '../../css/y/yrgiqhxka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="blor6etyc wm-k"/><path class="m49hu2bxr wm-a"/><path class="v1kuu0bke wm-shadow"/><path class="uq6pq445a wm-k"/><path class="wm-a yrgiqhxka"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:workflow-engrave" {...props}></Icon>
