<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/s/s9xy0ebzg.css';
import '../../css/j/j5xauwbke.css';
import '../../css/i/ir3krzgyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<g class="h01tyzbfu"><path class="s9xy0ebzg"/><path class="j5xauwbke"/><path class="ir3krzgyh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:toggle-outline" {...props}></Icon>
