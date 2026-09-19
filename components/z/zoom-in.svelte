<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nn2vh5b-t.css';
import '../../css/l/l59o3ubcg.css';
import '../../css/s/s6d8kmbpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="nn2vh5b-t"/><path class="l59o3ubcg"/><path class="s6d8kmbpc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:zoom-in" {...props}></Icon>
