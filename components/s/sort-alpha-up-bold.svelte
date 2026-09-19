<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/kdfbz6i8l.css';
import '../../css/x/xu0one_4p.css';
import '../../css/b/boxfqhb0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="kdfbz6i8l"/><path class="xu0one_4p"/><path class="boxfqhb0s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:sort-alpha-up-bold" {...props}></Icon>
