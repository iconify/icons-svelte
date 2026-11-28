<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/axcq7ubvg.css';
import '../../css/i/in29btpof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="axcq7ubvg"/><path class="in29btpof"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:sort-alphabetical-ascending-duotone" {...props}></Icon>
