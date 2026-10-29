<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/bqx1ccb4e.css';
import '../../css/k/kcp0sf6ge.css';
import '../../css/d/d56nsib3c.css';
import '../../css/d/dhuewpeee.css';
import '../../css/b/byf_cebpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="bqx1ccb4e wm-k"/><path class="kcp0sf6ge wm-a"/><path class="d56nsib3c wm-shadow"/><path class="dhuewpeee wm-k"/><path class="byf_cebpl wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:skip-forward-engrave" {...props}></Icon>
