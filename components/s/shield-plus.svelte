<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/ydq7eqwzq.css';
import '../../css/c/ccbsimlpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="ydq7eqwzq"/><path class="ccbsimlpi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:shield-plus" {...props}></Icon>
