<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/i7fhajigd.css';
import '../../css/l/lp6b5iboh.css';
import '../../css/f/fl08_4b0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="i7fhajigd"/><path class="lp6b5iboh"/><path class="fl08_4b0x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:skateboard-bold" {...props}></Icon>
