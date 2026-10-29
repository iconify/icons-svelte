<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/fizeclbdz.css';
import '../../css/r/rc1nbbcet.css';
import '../../css/f/f0yb61qbz.css';
import '../../css/n/n2ypjvrce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="fizeclbdz wm-k"/><path class="rc1nbbcet wm-a"/><path class="f0yb61qbz wm-k"/><path class="n2ypjvrce wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:signature-sketch" {...props}></Icon>
