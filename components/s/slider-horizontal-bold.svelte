<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/d_5-cnc6s.css';
import '../../css/e/eewomobar.css';
import '../../css/g/gzjneqlby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="d_5-cnc6s"/><path class="eewomobar"/><path class="gzjneqlby"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:slider-horizontal-bold" {...props}></Icon>
