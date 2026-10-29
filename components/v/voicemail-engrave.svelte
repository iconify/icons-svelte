<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/pbbswkb8p.css';
import '../../css/t/totmvqulo.css';
import '../../css/a/apbxdlbgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="pbbswkb8p"/><path class="totmvqulo wm-shadow"/><path class="apbxdlbgs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:voicemail-engrave" {...props}></Icon>
