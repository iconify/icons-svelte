<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/i1bspmbls.css';
import '../../css/u/uo0d8mbaa.css';
import '../../css/v/vhl0zkx6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="i1bspmbls"/><path class="uo0d8mbaa"/><path class="vhl0zkx6a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:wallet-2-bold-duotone" {...props}></Icon>
