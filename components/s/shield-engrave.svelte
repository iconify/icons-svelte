<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/l9vmhfb_s.css';
import '../../css/r/r3yr01bjg.css';
import '../../css/x/xrfn3bcyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="l9vmhfb_s"/><path class="r3yr01bjg wm-shadow"/><path class="xrfn3bcyz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:shield-engrave" {...props}></Icon>
