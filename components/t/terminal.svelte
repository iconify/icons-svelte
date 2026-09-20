<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flen3tbdj.css';
import '../../css/d/dn_xbcb7g.css';
import '../../css/g/g9ew6e1fs.css';
import '../../css/p/ppsbne-ws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><rect class="dn_xbcb7g"/><path class="g9ew6e1fs"/><path class="ppsbne-ws"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:terminal" {...props}></Icon>
