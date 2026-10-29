<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/sj419obqh.css';
import '../../css/z/zu23d_b1x.css';
import '../../css/g/g__p88bfn.css';
import '../../css/y/ys4jrrrwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="sj419obqh"/><path class="wm-a zu23d_b1x"/><path class="g__p88bfn wm-k"/><path class="wm-a ys4jrrrwc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:server-sketch" {...props}></Icon>
