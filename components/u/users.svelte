<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bguf4zbjw.css';
import '../../css/p/ph8fhtbjr.css';
import '../../css/r/r2vfrlbwl.css';
import '../../css/p/pn5h7rz2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="bguf4zbjw"/><path class="ph8fhtbjr"/><path class="r2vfrlbwl"/><path class="pn5h7rz2h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:users" {...props}></Icon>
