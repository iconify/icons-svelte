<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/aw7h4pbns.css';
import '../../css/q/q4vef2bkz.css';
import '../../css/x/xt16wcg7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="aw7h4pbns wm-k"/><path class="q4vef2bkz wm-shadow"/><path class="wm-k xt16wcg7u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:zap-engrave" {...props}></Icon>
