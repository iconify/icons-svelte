<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rymil3blb.css';
import '../../css/p/pcz6l7bqo.css';
import '../../css/t/tx9rzfbdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="rymil3blb"/><path class="pcz6l7bqo"/><path class="tx9rzfbdi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:tachometer-7-duo" {...props}></Icon>
