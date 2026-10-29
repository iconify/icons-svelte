<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/sh_9j11bm.css';
import '../../css/p/p-zp6abgy.css';
import '../../css/a/au-aqdi1z.css';
import '../../css/z/z1gf-w-er.css';
import '../../css/q/qjoi1kboe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="sh_9j11bm wm-k"/><path class="p-zp6abgy wm-a"/><path class="au-aqdi1z wm-shadow"/><path class="wm-k z1gf-w-er"/><path class="qjoi1kboe wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:signature-engrave" {...props}></Icon>
