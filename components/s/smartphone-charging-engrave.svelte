<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/a6bdxlbfp.css';
import '../../css/g/gawr9cban.css';
import '../../css/z/zzgumwbxx.css';
import '../../css/a/acmuaibfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="a6bdxlbfp wm-k"/><path class="gawr9cban wm-shadow"/><path class="wm-k zzgumwbxx"/><path class="acmuaibfy wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:smartphone-charging-engrave" {...props}></Icon>
