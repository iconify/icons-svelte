<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/z/zzot_onjx.css';
import '../../css/k/kmig01bhu.css';
import '../../css/f/fmarqootd.css';
import '../../css/b/bfxhibc1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="zzot_onjx"/><path class="kmig01bhu wm-k"/><path class="fmarqootd wm-k"/><path class="bfxhibc1f wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:star-half-sketch" {...props}></Icon>
