<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/is7p6owsa.css';
import '../../css/h/hx2mzrprj.css';
import '../../css/f/fo3gdfn_q.css';
import '../../css/l/ljeitrr-k.css';
import '../../css/x/x2ocqx88i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="is7p6owsa wm-k"/><path class="hx2mzrprj wm-s"/><path class="fo3gdfn_q wm-shadow"/><path class="ljeitrr-k wm-k"/><path class="wm-s x2ocqx88i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:user-star-engrave" {...props}></Icon>
