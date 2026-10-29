<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/j6ww2np8q.css';
import '../../css/j/j-amthb_f.css';
import '../../css/f/f8q2orbkn.css';
import '../../css/v/vox2lqicx.css';
import '../../css/b/bws2o1beu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="j6ww2np8q"/><path class="j-amthb_f wm-k"/><path class="f8q2orbkn wm-a"/><path class="vox2lqicx wm-k"/><path class="bws2o1beu wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:wallet-sketch" {...props}></Icon>
