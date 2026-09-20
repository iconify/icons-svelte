<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/u4jda1b4y.css';
import '../../css/c/cdl2a1bbr.css';
import '../../css/r/rqfiu97ew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="u4jda1b4y"/><path class="cdl2a1bbr"/><path clip-rule="evenodd" class="rqfiu97ew"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:routing-2-outline" {...props}></Icon>
