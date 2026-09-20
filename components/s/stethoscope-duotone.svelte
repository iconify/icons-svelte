<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/me86ccc_a.css';
import '../../css/f/f4s_wibfo.css';
import '../../css/x/x-yo1fvtj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><circle class="me86ccc_a"/><path class="f4s_wibfo"/><path class="x-yo1fvtj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:stethoscope-duotone" {...props}></Icon>
