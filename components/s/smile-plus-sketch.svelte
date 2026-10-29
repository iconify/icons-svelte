<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/kaxnrx-5v.css';
import '../../css/s/ssz1-_f6r.css';
import '../../css/l/li3spsbhq.css';
import '../../css/u/umgdc9blm.css';
import '../../css/u/u1_6cvbjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="kaxnrx-5v wm-k"/><path class="ssz1-_f6r wm-k"/><path class="li3spsbhq wm-a"/><path class="umgdc9blm wm-a"/><path class="u1_6cvbjv wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:smile-plus-sketch" {...props}></Icon>
