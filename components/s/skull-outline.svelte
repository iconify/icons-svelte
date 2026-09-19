<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/v90n_sbfk.css';
import '../../css/r/rs9a2ybyz.css';
import '../../css/g/gnokhxweg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="v90n_sbfk"/><path class="rs9a2ybyz"/><path clip-rule="evenodd" class="gnokhxweg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:skull-outline" {...props}></Icon>
