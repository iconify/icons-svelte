<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/ul0c7wb_k.css';
import '../../css/e/esbapuc5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="ul0c7wb_k"/><path class="esbapuc5c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:run-with-deps" {...props}></Icon>
