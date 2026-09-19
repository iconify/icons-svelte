<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/h7ph6ebna.css';
import '../../css/t/truwibb1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="h7ph6ebna"/><path class="truwibb1p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:shield-duotone" {...props}></Icon>
