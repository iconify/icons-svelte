<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/xdc93g1nz.css';
import '../../css/m/mr5if-bbh.css';
import '../../css/t/ta49hcb6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="xdc93g1nz"/><path clip-rule="evenodd" class="mr5if-bbh"/><path clip-rule="evenodd" class="ta49hcb6o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:wheelchair-alt2x-outline" {...props}></Icon>
