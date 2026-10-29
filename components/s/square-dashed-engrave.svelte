<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/asn38kb9q.css';
import '../../css/u/u4d-mh8hw.css';
import '../../css/g/gqr-fjz3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="asn38kb9q"/><path class="u4d-mh8hw wm-shadow"/><path class="gqr-fjz3v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:square-dashed-engrave" {...props}></Icon>
