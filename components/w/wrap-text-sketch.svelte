<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/a1bidkywl.css';
import '../../css/v/vx-034bzq.css';
import '../../css/l/lpju1obmb.css';
import '../../css/x/xfyogqb8v.css';
import '../../css/p/ptl8sbnfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="a1bidkywl wm-k"/><path class="vx-034bzq wm-k"/><path class="lpju1obmb wm-a"/><path class="wm-a xfyogqb8v"/><path class="ptl8sbnfp wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:wrap-text-sketch" {...props}></Icon>
