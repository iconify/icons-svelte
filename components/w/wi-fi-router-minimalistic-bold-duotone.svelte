<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mc2zb0bvp.css';
import '../../css/y/ysclhbb2b.css';
import '../../css/i/i0bfp_vut.css';
import '../../css/b/bpmhux1_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><g class="mc2zb0bvp"><path class="ysclhbb2b"/><path class="i0bfp_vut"/></g><path clip-rule="evenodd" class="bpmhux1_w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:wi-fi-router-minimalistic-bold-duotone" {...props}></Icon>
