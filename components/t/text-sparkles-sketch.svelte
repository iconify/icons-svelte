<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/v7cfz7b0r.css';
import '../../css/o/obtvy0npp.css';
import '../../css/n/nqxmswb2p.css';
import '../../css/g/g3x_gdb2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="v7cfz7b0r wm-k"/><path class="obtvy0npp wm-s"/><path class="nqxmswb2p wm-k"/><path class="g3x_gdb2f wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:text-sparkles-sketch" {...props}></Icon>
