<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/kqfytvbmd.css';
import '../../css/j/jturxcmib.css';
import '../../css/a/awhq7acwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="kqfytvbmd"/><path class="jturxcmib"/><path clip-rule="evenodd" class="awhq7acwr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:xray2x-outline" {...props}></Icon>
