<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/pn10iob8l.css';
import '../../css/q/qr4ochb5c.css';
import '../../css/l/lqdy3rb7m.css';
import '../../css/h/h0g_bvisu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="pn10iob8l"/><path class="qr4ochb5c wm-s"/><path class="lqdy3rb7m"/><path class="h0g_bvisu wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:video-off-duo" {...props}></Icon>
