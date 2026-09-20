<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l_gpdk82h.css';
import '../../css/x/xcrgk3rdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="l_gpdk82h"/><path class="xcrgk3rdt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:sunrise-alt" {...props}></Icon>
