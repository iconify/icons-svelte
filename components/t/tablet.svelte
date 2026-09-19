<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qojb79vkl.css';
import '../../css/p/p3-bwf-tg.css';
import '../../css/y/ycfdc-bvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="qojb79vkl"/><path class="p3-bwf-tg"/><path clip-rule="evenodd" class="ycfdc-bvw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:tablet" {...props}></Icon>
