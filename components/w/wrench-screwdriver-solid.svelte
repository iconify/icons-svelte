<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/isg50z21f.css';
import '../../css/r/ry7qrib1l.css';
import '../../css/e/ez93jooon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="isg50z21f"/><path class="ry7qrib1l"/><path clip-rule="evenodd" class="ez93jooon"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:wrench-screwdriver-solid" {...props}></Icon>
