<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/uwmffobfh.css';
import '../../css/t/t6xc7ubwd.css';
import '../../css/t/tmle8u6kk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="uwmffobfh"/><path clip-rule="evenodd" class="t6xc7ubwd"/><path class="tmle8u6kk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:running-bold" {...props}></Icon>
