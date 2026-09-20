<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/ff9s5t-qh.css';
import '../../css/j/jhs71nb5c.css';
import '../../css/d/dicbf-s8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ff9s5t-qh"/><path class="jhs71nb5c"/><rect class="dicbf-s8h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:three-squares-bold-duotone" {...props}></Icon>
