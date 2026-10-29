<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/gev3iobdk.css';
import '../../css/r/r0lcoh1hs.css';
import '../../css/l/l_usi832h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="gev3iobdk"/><path class="r0lcoh1hs wm-k"/><path class="l_usi832h wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:volleyball-sketch" {...props}></Icon>
