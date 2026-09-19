<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/y8ovkkbdl.css';
import '../../css/i/i9fk3vbkl.css';
import '../../css/n/ndirhzcpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="y8ovkkbdl"/><path class="i9fk3vbkl"/><path class="ndirhzcpc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:snow-duo" {...props}></Icon>
