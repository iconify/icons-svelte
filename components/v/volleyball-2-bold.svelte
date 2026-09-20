<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rzzy5jjev.css';
import '../../css/b/big4d8t5q.css';
import '../../css/d/dv6lf562e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rzzy5jjev"/><path class="big4d8t5q"/><path class="dv6lf562e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:volleyball-2-bold" {...props}></Icon>
