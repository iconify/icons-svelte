<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/e2ra9zmqo.css';
import '../../css/r/rbrqs4bqf.css';
import '../../css/f/fedou6bod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="e2ra9zmqo"/><path class="rbrqs4bqf"/><path class="fedou6bod"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:routing-3-bold" {...props}></Icon>
