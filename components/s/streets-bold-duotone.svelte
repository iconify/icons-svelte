<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fcaaw--es.css';
import '../../css/k/km6q1bmez.css';
import '../../css/u/ut5j5mboq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="fcaaw--es"/><path class="km6q1bmez"/><path class="ut5j5mboq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:streets-bold-duotone" {...props}></Icon>
