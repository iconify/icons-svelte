<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/n6n7-ij3e.css';
import '../../css/r/r_vfe3bhg.css';
import '../../css/w/wky8mmmcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="n6n7-ij3e"/><path class="r_vfe3bhg"/><path clip-rule="evenodd" class="wky8mmmcc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:sleepy2x-outline" {...props}></Icon>
