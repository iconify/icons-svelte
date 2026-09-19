<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/x4pbug86i.css';
import '../../css/l/l7fiaob4l.css';
import '../../css/w/w4xi5ecbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="x4pbug86i"/><path class="l7fiaob4l"/><path clip-rule="evenodd" class="w4xi5ecbh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:wash-hands-outline" {...props}></Icon>
