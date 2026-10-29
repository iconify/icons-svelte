<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/w_umu3q7p.css';
import '../../css/d/djpm-nbqp.css';
import '../../css/w/wgaw3djmi.css';
import '../../css/r/rxypl7oqe.css';
import '../../css/g/gtohkybxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="w_umu3q7p wm-k"/><path class="djpm-nbqp wm-a"/><path class="wgaw3djmi wm-shadow"/><path class="rxypl7oqe wm-k"/><path class="gtohkybxy wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:umbrella-engrave" {...props}></Icon>
