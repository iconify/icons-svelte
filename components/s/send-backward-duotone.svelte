<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/r3oazrncr.css';
import '../../css/g/gxg1pfhph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="r3oazrncr"/><path class="gxg1pfhph"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:send-backward-duotone" {...props}></Icon>
