<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/svg81bcgr.css';
import '../../css/c/clok_hbux.css';
import '../../css/m/mvu50ub7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="svg81bcgr"/><path class="clok_hbux"/><path class="mvu50ub7r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:sort-numeric-down-bold" {...props}></Icon>
