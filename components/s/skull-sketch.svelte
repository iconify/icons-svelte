<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/ftjlt04ey.css';
import '../../css/i/inirm0b4k.css';
import '../../css/p/poqevy83a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ftjlt04ey"/><path class="inirm0b4k wm-k"/><path class="poqevy83a wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:skull-sketch" {...props}></Icon>
