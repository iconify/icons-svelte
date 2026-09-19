<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vxsbrmb-c.css';
import '../../css/m/mw3nq9vrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="vxsbrmb-c"/><path clip-rule="evenodd" class="mw3nq9vrp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:signal-75-bold" {...props}></Icon>
