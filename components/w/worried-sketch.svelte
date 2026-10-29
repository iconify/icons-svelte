<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/rnmw6x9fk.css';
import '../../css/y/yi2d8monv.css';
import '../../css/m/me3p1obmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="rnmw6x9fk wm-k"/><path class="wm-a yi2d8monv"/><path class="me3p1obmu wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:worried-sketch" {...props}></Icon>
