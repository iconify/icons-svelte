<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/g4rq9cb4b.css';
import '../../css/h/hiqgl-xto.css';
import '../../css/i/ialz71b-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="g4rq9cb4b"/><path class="hiqgl-xto wm-shadow"/><path class="ialz71b-c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:usb-engrave" {...props}></Icon>
