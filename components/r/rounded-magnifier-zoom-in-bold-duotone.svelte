<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l_z2a8vzi.css';
import '../../css/z/z7j33g1js.css';
import '../../css/s/sbtskbcjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><circle class="l_z2a8vzi"/><path class="z7j33g1js"/><path class="sbtskbcjb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rounded-magnifier-zoom-in-bold-duotone" {...props}></Icon>
