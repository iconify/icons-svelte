<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/osl2pacnv.css';
import '../../css/p/pgeiwdbwc.css';
import '../../css/w/wnbm9ubwr.css';
import '../../css/z/z8y5cubeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="osl2pacnv"/><path class="pgeiwdbwc"/><path class="wnbm9ubwr"/><path class="z8y5cubeq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:suitcase-lines-bold-duotone" {...props}></Icon>
