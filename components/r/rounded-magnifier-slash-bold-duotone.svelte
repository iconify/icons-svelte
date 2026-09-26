<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l_z2a8vzi.css';
import '../../css/d/d5tljviqd.css';
import '../../css/v/vxe9koteb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><circle class="l_z2a8vzi"/><path class="d5tljviqd"/><path class="vxe9koteb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rounded-magnifier-slash-bold-duotone" {...props}></Icon>
