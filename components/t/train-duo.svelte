<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vou3r2ifc.css';
import '../../css/t/t17ta3bli.css';
import '../../css/n/nxbj7m54b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="vou3r2ifc"/><path class="t17ta3bli"/><path class="nxbj7m54b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:train-duo" {...props}></Icon>
