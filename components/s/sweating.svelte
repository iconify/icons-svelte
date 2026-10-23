<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/k7q397iue.css';
import '../../css/f/fq6vlbqqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="k7q397iue"/><path clip-rule="evenodd" class="fq6vlbqqd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:sweating" {...props}></Icon>
