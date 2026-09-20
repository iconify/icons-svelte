<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/y92_fgbke.css';
import '../../css/r/rvc7i_b9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><circle transform="rotate(-9 18.078 8.286)" class="y92_fgbke"/><path class="rvc7i_b9t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:sort" {...props}></Icon>
