<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zgejto_9f.css';
import '../../css/b/bhhme_0me.css';
import '../../css/d/dg3r1tbgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="zgejto_9f"/><path class="bhhme_0me"/><path class="dg3r1tbgl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:signal-tower-duo" {...props}></Icon>
