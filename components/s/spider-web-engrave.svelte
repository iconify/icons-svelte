<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/m4dq46b2l.css';
import '../../css/c/c40o4qbmy.css';
import '../../css/i/ihz715blo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="m4dq46b2l"/><path class="c40o4qbmy wm-shadow"/><path class="ihz715blo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:spider-web-engrave" {...props}></Icon>
