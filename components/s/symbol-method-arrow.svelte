<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/o1dzi7biv.css';
import '../../css/q/qtsnc0bxz.css';
import '../../css/b/bau06jt7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="o1dzi7biv"/><path class="qtsnc0bxz"/><path class="bau06jt7d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:symbol-method-arrow" {...props}></Icon>
