<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfxngabua.css';
import '../../css/s/syuwirbva.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fe_p2ybfu.css';
import '../../css/z/zwsgkpb8c.css';
import '../../css/d/d4cn7bb1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="bfxngabua"/><path class="syuwirbva"/><g class="cuyn6tgcc"><path class="fe_p2ybfu"/><path class="zwsgkpb8c"/><path class="d4cn7bb1x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:sound" {...props}></Icon>
