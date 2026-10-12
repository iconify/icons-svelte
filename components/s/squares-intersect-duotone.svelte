<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/z5ymcabpn.css';
import '../../css/r/rkqb1nq9h.css';
import '../../css/w/wdpg8g0zd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="z5ymcabpn"/><path class="rkqb1nq9h"/><path class="wdpg8g0zd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:squares-intersect-duotone" {...props}></Icon>
