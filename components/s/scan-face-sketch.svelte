<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/vvxb3xb7h.css';
import '../../css/l/l8c6jtbnt.css';
import '../../css/m/mw8pgwbuy.css';
import '../../css/u/urt9xzh-z.css';
import '../../css/f/fj9ql-fmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="vvxb3xb7h"/><path class="l8c6jtbnt wm-k"/><path class="mw8pgwbuy wm-a"/><path class="urt9xzh-z wm-k"/><path class="fj9ql-fmu wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:scan-face-sketch" {...props}></Icon>
