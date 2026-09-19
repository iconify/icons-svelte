<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f-70sba8t.css';
import '../../css/d/d2zbbb4nw.css';
import '../../css/m/mo1pfhmuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="f-70sba8t"/><path clip-rule="evenodd" class="d2zbbb4nw"/><path clip-rule="evenodd" class="mo1pfhmuv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:star-half-1" {...props}></Icon>
