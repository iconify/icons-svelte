<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rysq24_6r.css';
import '../../css/z/z4wkd6b2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><rect class="rysq24_6r"/><path clip-rule="evenodd" class="z4wkd6b2q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:square-half-1" {...props}></Icon>
