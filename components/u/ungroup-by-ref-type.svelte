<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/iua0p6vky.css';
import '../../css/u/ulzgaspjq.css';
import '../../css/s/stcekdbwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="iua0p6vky"/><path clip-rule="evenodd" class="ulzgaspjq"/><path class="stcekdbwb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:ungroup-by-ref-type" {...props}></Icon>
