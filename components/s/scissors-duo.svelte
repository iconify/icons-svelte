<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zttmhdm7h.css';
import '../../css/f/fll8gje-k.css';
import '../../css/c/cwwt87b2f.css';
import '../../css/s/s6k4l3b-m.css';
import '../../css/k/kxu8vjbib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="zttmhdm7h"/><path class="fll8gje-k"/><path clip-rule="evenodd" class="cwwt87b2f"/><path class="s6k4l3b-m"/><path class="kxu8vjbib"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:scissors-duo" {...props}></Icon>
