<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/r7uu9fcak.css';
import '../../css/p/pf64yv0wt.css';
import '../../css/r/r8i9bcc2r.css';
import '../../css/l/ly23pmblx.css';
import '../../css/g/gt402wbqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="r7uu9fcak wm-k"/><path class="pf64yv0wt wm-a"/><path class="r8i9bcc2r wm-shadow"/><path class="ly23pmblx wm-k"/><path class="gt402wbqt wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:train-engrave" {...props}></Icon>
