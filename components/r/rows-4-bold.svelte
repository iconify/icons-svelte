<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/ibrcm0b3s.css';
import '../../css/w/wdipljbrd.css';
import '../../css/x/xsl5v7bfz.css';
import '../../css/u/udovdvbge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ibrcm0b3s"/><path class="wdipljbrd"/><path class="xsl5v7bfz"/><path class="udovdvbge"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rows-4-bold" {...props}></Icon>
