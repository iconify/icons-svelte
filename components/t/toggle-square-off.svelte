<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mr8f6fb0f.css';
import '../../css/s/sdyfvcrbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mr8f6fb0f"/><path clip-rule="evenodd" class="sdyfvcrbb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:toggle-square-off" {...props}></Icon>
