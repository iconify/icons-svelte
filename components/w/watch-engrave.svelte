<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/ik1oxmbfh.css';
import '../../css/k/ku5p8_kxi.css';
import '../../css/h/h7xnus5-e.css';
import '../../css/u/unefcsbmw.css';
import '../../css/a/anua2ob4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ik1oxmbfh wm-k"/><path class="ku5p8_kxi wm-shadow"/><path class="h7xnus5-e wm-k"/><path class="unefcsbmw wm-k"/><path class="anua2ob4h wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:watch-engrave" {...props}></Icon>
