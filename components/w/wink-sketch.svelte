<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/izpiltzao.css';
import '../../css/b/bhx_bhpfu.css';
import '../../css/g/g-v_k7b2s.css';
import '../../css/s/s8pgmizvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="izpiltzao"/><path class="bhx_bhpfu wm-a"/><path class="g-v_k7b2s wm-k"/><path class="s8pgmizvv wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:wink-sketch" {...props}></Icon>
