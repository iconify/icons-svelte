<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gns6qx_4s.css';
import '../../css/u/uv-8ifblj.css';
import '../../css/m/mvu50ub7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="gns6qx_4s"/><path class="uv-8ifblj"/><path class="mvu50ub7r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:sort-numeric-up-bold" {...props}></Icon>
