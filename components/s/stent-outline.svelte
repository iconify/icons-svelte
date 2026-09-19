<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/tx4ucrbrc.css';
import '../../css/p/plg4ghbsm.css';
import '../../css/a/ai58kdhbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="tx4ucrbrc"/><path clip-rule="evenodd" class="plg4ghbsm"/><path clip-rule="evenodd" class="ai58kdhbv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:stent-outline" {...props}></Icon>
