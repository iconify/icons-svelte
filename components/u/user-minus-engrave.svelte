<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/djiqt-b-p.css';
import '../../css/u/utwv_dard.css';
import '../../css/g/g-ayowdns.css';
import '../../css/e/emha3wbqe.css';
import '../../css/i/ihj2_9b2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="djiqt-b-p wm-k"/><path class="utwv_dard wm-s"/><path class="g-ayowdns wm-shadow"/><path class="emha3wbqe wm-k"/><path class="ihj2_9b2p wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:user-minus-engrave" {...props}></Icon>
