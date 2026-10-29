<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/y/ywn0ijbmf.css';
import '../../css/f/f5-lpey4g.css';
import '../../css/y/ypv0z_bsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ywn0ijbmf"/><path class="f5-lpey4g wm-shadow"/><path class="ypv0z_bsz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:sailboat-engrave" {...props}></Icon>
