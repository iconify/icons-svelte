<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rymil3blb.css';
import '../../css/i/iqcw7ybod.css';
import '../../css/n/n4y5veybd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="rymil3blb"/><path class="iqcw7ybod"/><path class="n4y5veybd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:tachometer-8-duo" {...props}></Icon>
