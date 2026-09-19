<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/abr_kgi4p.css';
import '../../css/r/r5p16_b3f.css';
import '../../css/n/nl3003msu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="abr_kgi4p"/><path class="r5p16_b3f"/><path class="nl3003msu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:timer-1" {...props}></Icon>
