<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/t_owy1dlv.css';
import '../../css/a/a1dbd2dld.css';
import '../../css/j/j_udulbub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="t_owy1dlv"/><path class="a1dbd2dld"/><path class="j_udulbub"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:window-plus" {...props}></Icon>
