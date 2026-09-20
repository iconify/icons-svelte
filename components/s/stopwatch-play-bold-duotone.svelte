<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vu-8l_mcm.css';
import '../../css/t/tz6w_ozgi.css';
import '../../css/v/v3e_w0bfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vu-8l_mcm"/><path class="tz6w_ozgi"/><path class="v3e_w0bfi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:stopwatch-play-bold-duotone" {...props}></Icon>
