<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/g-anivbbg.css';
import '../../css/p/p3d1spb0g.css';
import '../../css/m/m_gu8i8bb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="g-anivbbg"/><path class="p3d1spb0g wm-shadow"/><path class="m_gu8i8bb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:stop-engrave" {...props}></Icon>
