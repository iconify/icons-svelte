<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lyl5rtb9m.css';
import '../../css/c/col8s83ww.css';
import '../../css/b/boxfqhb0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="lyl5rtb9m"/><path class="col8s83ww"/><path class="boxfqhb0s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:sort-alpha-down-bold" {...props}></Icon>
