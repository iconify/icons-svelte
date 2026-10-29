<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/xpm3rbbsn.css';
import '../../css/u/u7czf0bqt.css';
import '../../css/m/mggu2tbml.css';
import '../../css/n/nu8tdetna.css';
import '../../css/f/fagua8bxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="xpm3rbbsn"/><path class="u7czf0bqt wm-shadow"/><path class="mggu2tbml"/><path class="nu8tdetna"/><path class="fagua8bxp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:stethoscope-engrave" {...props}></Icon>
