<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/j/jwvhftb8e.css';
import '../../css/e/e4b5jwbkp.css';
import '../../css/c/cx1-3ebcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<g class="h01tyzbfu"><path class="jwvhftb8e"/><path class="e4b5jwbkp"/><path class="cx1-3ebcg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:venn-diagram-outline" {...props}></Icon>
