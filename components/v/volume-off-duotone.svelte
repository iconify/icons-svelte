<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/p96kp1t6i.css';
import '../../css/r/r2n7k2ben.css';
import '../../css/x/x1_dwzzrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="p96kp1t6i"/><path class="r2n7k2ben"/><path class="x1_dwzzrc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:volume-off-duotone" {...props}></Icon>
