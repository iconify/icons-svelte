<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/ppv8sabtv.css';
import '../../css/s/swymxgbga.css';
import '../../css/a/azvt57uxv.css';
import '../../css/v/v1fljab8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ppv8sabtv"/><path class="swymxgbga"/><path clip-rule="evenodd" class="azvt57uxv"/><path class="v1fljab8g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:tree-1-bold" {...props}></Icon>
