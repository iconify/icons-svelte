<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/q/q-ome_08g.css';
import '../../css/d/dg2drhi8k.css';
import '../../css/a/auv6lqb6w.css';
import '../../css/f/fft4yz3uq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="q-ome_08g"/><path class="dg2drhi8k"/><path class="auv6lqb6w"/><path class="fft4yz3uq wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:webhook" {...props}></Icon>
