<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hhk_3sb_s.css';
import '../../css/n/nbsz5ubbo.css';
import '../../css/d/d3oe1fwko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="hhk_3sb_s"/><path class="nbsz5ubbo"/><path clip-rule="evenodd" class="d3oe1fwko"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:tornado-bold" {...props}></Icon>
