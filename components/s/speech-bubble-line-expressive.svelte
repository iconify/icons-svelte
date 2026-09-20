<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gatfc8btz.css';
import '../../css/m/mtcnkkdgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gatfc8btz"/><path clip-rule="evenodd" class="mtcnkkdgi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:speech-bubble-line-expressive" {...props}></Icon>
