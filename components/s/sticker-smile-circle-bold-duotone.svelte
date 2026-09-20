<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lx7m2-bor.css';
import '../../css/i/iqgdhbc6s.css';
import '../../css/l/l3vfyexrd.css';
import '../../css/c/crykbyqhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="lx7m2-bor"/><path class="iqgdhbc6s"/><path class="l3vfyexrd"/><path class="crykbyqhi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sticker-smile-circle-bold-duotone" {...props}></Icon>
