<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/k_q_62blo.css';
import '../../css/x/xvh_w0b5q.css';
import '../../css/v/v4y4a33-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="k_q_62blo"/><path class="xvh_w0b5q"/><path clip-rule="evenodd" class="v4y4a33-n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:secure-communication-negative" {...props}></Icon>
