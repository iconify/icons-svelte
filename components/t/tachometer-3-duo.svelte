<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/p8ebzs-6d.css';
import '../../css/x/xpn136bpa.css';
import '../../css/r/rqvn39bdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="p8ebzs-6d"/><path class="xpn136bpa"/><path class="rqvn39bdd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:tachometer-3-duo" {...props}></Icon>
