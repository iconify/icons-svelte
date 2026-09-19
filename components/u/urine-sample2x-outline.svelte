<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/tyen9wbhl.css';
import '../../css/r/rhgvw3brc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="tyen9wbhl"/><path clip-rule="evenodd" class="rhgvw3brc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:urine-sample2x-outline" {...props}></Icon>
