<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hpkhd7pvn.css';
import '../../css/l/lf3y5v97k.css';
import '../../css/b/bqwtorbgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="hpkhd7pvn"/><path clip-rule="evenodd" class="lf3y5v97k"/><path class="bqwtorbgd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:save-1-bold" {...props}></Icon>
