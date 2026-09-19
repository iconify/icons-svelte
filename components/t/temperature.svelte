<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h8aqxbbrl.css';
import '../../css/q/q-w374b1g.css';
import '../../css/j/juykxi29h.css';
import '../../css/v/vxtp-z-ls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="h8aqxbbrl"/><path class="q-w374b1g"/><path clip-rule="evenodd" class="juykxi29h"/><rect class="vxtp-z-ls"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:temperature" {...props}></Icon>
