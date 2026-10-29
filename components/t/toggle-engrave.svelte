<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/pi05i1bnr.css';
import '../../css/r/rz3zm32es.css';
import '../../css/z/z2i45qmri.css';
import '../../css/p/pjqa07bbp.css';
import '../../css/s/skqzgzjwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="pi05i1bnr wm-k"/><path class="rz3zm32es wm-a"/><path class="wm-shadow z2i45qmri"/><path class="pjqa07bbp wm-k"/><path class="skqzgzjwd wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:toggle-engrave" {...props}></Icon>
