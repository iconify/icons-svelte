<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/qpzepbxoc.css';
import '../../css/m/mc2zb0bvp.css';
import '../../css/z/zbke2mcmt.css';
import '../../css/o/oj410s8yw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="qpzepbxoc"/><g class="mc2zb0bvp"><path class="zbke2mcmt"/><path class="oj410s8yw"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sleeping-bold-duotone" {...props}></Icon>
