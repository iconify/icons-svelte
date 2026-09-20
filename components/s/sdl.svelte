<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/doprogbdx.css';
import '../../css/b/b5tmlbjxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<g class="cuyn6tgcc"><path class="doprogbdx"/><path class="b5tmlbjxo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:sdl" {...props}></Icon>
