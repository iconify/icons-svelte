<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l_z2a8vzi.css';
import '../../css/n/nvp9ioxtn.css';
import '../../css/j/jq6fb3b7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><circle class="l_z2a8vzi"/><path class="nvp9ioxtn"/><path class="jq6fb3b7s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rounded-magnifier-close-bold-duotone" {...props}></Icon>
