<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vc_bw3brk.css';
import '../../css/h/hfms_-bxq.css';
import '../../css/d/dfg05dvdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vc_bw3brk"/><path class="hfms_-bxq"/><path class="dfg05dvdn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:user-circle-line" {...props}></Icon>
