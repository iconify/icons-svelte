<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f886c8bin.css';
import '../../css/k/kangm0rqb.css';
import '../../css/s/sx3zoybsb.css';
import '../../css/g/gjh5sqboo.css';
import '../../css/g/gfs1b9nrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="f886c8bin"/><path clip-rule="evenodd" class="kangm0rqb"/><path class="sx3zoybsb"/><path clip-rule="evenodd" class="gjh5sqboo"/><path class="gfs1b9nrx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:route-bold" {...props}></Icon>
