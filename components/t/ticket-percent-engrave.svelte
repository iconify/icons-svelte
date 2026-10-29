<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/rzxk7-smr.css';
import '../../css/f/f7se-fbvj.css';
import '../../css/q/q-55d_bvt.css';
import '../../css/s/sq9ejvb2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="rzxk7-smr wm-k"/><path class="f7se-fbvj wm-shadow"/><path class="q-55d_bvt wm-k"/><path class="sq9ejvb2i wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:ticket-percent-engrave" {...props}></Icon>
