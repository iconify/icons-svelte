<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/g178b1wlz.css';
import '../../css/l/ld5zuhbyx.css';
import '../../css/s/sej-8-beb.css';
import '../../css/m/ma220ub_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="g178b1wlz"/><path clip-rule="evenodd" class="ld5zuhbyx"/><path class="sej-8-beb"/><path class="ma220ub_p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:scissors-print" {...props}></Icon>
