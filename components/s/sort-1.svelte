<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwvp95byt.css';
import '../../css/r/rv3khnsij.css';
import '../../css/g/g7241j9by.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="wwvp95byt"><path class="rv3khnsij"/><path class="g7241j9by"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:sort-1" {...props}></Icon>
