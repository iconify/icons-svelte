<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hihi0xbxs.css';
import '../../css/i/ir72yz0kf.css';
import '../../css/k/k7qrafbfv.css';
import '../../css/u/utwgsoz9d.css';
import '../../css/n/n--5h7b2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="hihi0xbxs"/><path clip-rule="evenodd" class="ir72yz0kf"/><path class="k7qrafbfv"/><path clip-rule="evenodd" class="utwgsoz9d"/><path class="n--5h7b2e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:ui-preferences-outline" {...props}></Icon>
