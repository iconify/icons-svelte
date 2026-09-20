<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bg-drv1xu.css';
import '../../css/u/um-e79spk.css';
import '../../css/p/pxv3brbsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bg-drv1xu"/><path clip-rule="evenodd" class="um-e79spk"/><path class="pxv3brbsd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:slider-h2" {...props}></Icon>
