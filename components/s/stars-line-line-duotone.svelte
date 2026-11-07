<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr52f_b5y.css';
import '../../css/m/m-ypx2l7g.css';
import '../../css/w/ws_62zb9c.css';
import '../../css/u/u5aegb-hj.css';
import '../../css/r/rco2m6vud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><path class="m-ypx2l7g"/><path class="ws_62zb9c"/><path class="u5aegb-hj"/><path class="rco2m6vud"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:stars-line-line-duotone" {...props}></Icon>
