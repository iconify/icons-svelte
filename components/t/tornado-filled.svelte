<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/uc3p9vbxr.css';
import '../../css/l/ld6w58bwc.css';
import '../../css/h/h31q7tb1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="uc3p9vbxr"/><path class="ld6w58bwc"/><path clip-rule="evenodd" class="h31q7tb1w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:tornado-filled" {...props}></Icon>
