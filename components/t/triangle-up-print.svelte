<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/ybnf2c1uh.css';
import '../../css/r/r2yd7-gea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="ybnf2c1uh"/><path clip-rule="evenodd" class="r2yd7-gea"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:triangle-up-print" {...props}></Icon>
