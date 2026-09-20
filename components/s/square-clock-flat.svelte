<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bjl2y6b8n.css';
import '../../css/s/svx6rpzch.css';
import '../../css/x/xv5ziabia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="ft5dv1b6b"><path class="bjl2y6b8n"/><path class="svx6rpzch"/><path clip-rule="evenodd" class="xv5ziabia"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:square-clock-flat" {...props}></Icon>
