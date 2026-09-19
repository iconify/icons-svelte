<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/am770-rkn.css';
import '../../css/b/b_50uw9gu.css';
import '../../css/n/n9g_p9nwk.css';
import '../../css/i/igt5-ob4h.css';
import '../../css/g/gi7kytb4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="am770-rkn"/><path class="b_50uw9gu"/><circle class="n9g_p9nwk"/><circle class="igt5-ob4h"/><path class="gi7kytb4j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:sad-tear" {...props}></Icon>
