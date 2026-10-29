<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/oyy_ozbcu.css';
import '../../css/d/dgd2b7dnc.css';
import '../../css/c/cvygwcb1l.css';
import '../../css/a/a5ognjdal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="oyy_ozbcu"/><path class="dgd2b7dnc wm-shadow"/><path class="cvygwcb1l"/><path class="a5ognjdal"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:wifi-engrave" {...props}></Icon>
