<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/k/kbumho25s.css';
import '../../css/x/xtd9eubfb.css';
import '../../css/r/r8g_vabug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="h01tyzbfu"><path class="kbumho25s"/><path class="xtd9eubfb"/><path class="r8g_vabug"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:timer-2" {...props}></Icon>
