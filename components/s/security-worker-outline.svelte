<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/w_ke1bbey.css';
import '../../css/l/lyv_st-0c.css';
import '../../css/j/j53y1ybih.css';
import '../../css/u/ubczyjues.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="w_ke1bbey"/><path clip-rule="evenodd" class="lyv_st-0c"/><path class="j53y1ybih"/><path clip-rule="evenodd" class="ubczyjues"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:security-worker-outline" {...props}></Icon>
