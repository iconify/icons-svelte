<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/ku9otcwlu.css';
import '../../css/k/klkx55b0y.css';
import '../../css/y/ycuo71n9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ku9otcwlu"/><path class="klkx55b0y"/><path clip-rule="evenodd" class="ycuo71n9f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:star-ring-bold-duotone" {...props}></Icon>
