<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/b/b91p3obex.css';
import '../../css/j/jv4_d7b6x.css';
import '../../css/t/t5w0scc5d.css';
import '../../css/k/k3pac-bjk.css';
import '../../css/m/mmspps2as.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="b91p3obex"/><path class="jv4_d7b6x"/><path class="t5w0scc5d"/><path class="k3pac-bjk"/><path class="mmspps2as"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:shop-four-tiles-window" {...props}></Icon>
