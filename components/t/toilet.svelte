<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/msymncc2p.css';
import '../../css/m/mh_7zbc2g.css';
import '../../css/v/v439fl81f.css';
import '../../css/v/vt17sibuz.css';
import '../../css/i/iuwtlacnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="msymncc2p"/><path class="mh_7zbc2g"/><path class="v439fl81f"/><path clip-rule="evenodd" class="vt17sibuz"/><path class="iuwtlacnm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:toilet" {...props}></Icon>
