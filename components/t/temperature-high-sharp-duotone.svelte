<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/t/t7c033bqn.css';
import '../../css/y/yva1_1fly.css';
import '../../css/u/u8_q54bsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="t7c033bqn"/><path class="yva1_1fly"/><path class="u8_q54bsb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:temperature-high-sharp-duotone" {...props}></Icon>
