<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/dzby_kbty.css';
import '../../css/f/f2v3xdrlx.css';
import '../../css/s/s2a91vbxp.css';
import '../../css/s/sds2cyb9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="dzby_kbty"/><path class="f2v3xdrlx wm-a"/><path class="s2a91vbxp wm-k"/><path class="sds2cyb9y wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:router-sketch" {...props}></Icon>
