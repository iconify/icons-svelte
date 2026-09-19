<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/gfb_y0bgv.css';
import '../../css/t/tz3jlipja.css';
import '../../css/g/gf6_545td.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="gfb_y0bgv"/><path class="tz3jlipja"/><path class="gf6_545td"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:timer-fast-duo" {...props}></Icon>
