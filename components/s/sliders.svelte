<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wcio2-jru.css';
import '../../css/b/bjc88209d.css';
import '../../css/t/t52m0pb7p.css';
import '../../css/h/h5k7alb4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="wcio2-jru"/><rect class="bjc88209d"/><rect class="t52m0pb7p"/><rect class="h5k7alb4s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:sliders" {...props}></Icon>
