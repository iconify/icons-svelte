<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7fmnlb4r.css';
import '../../css/t/tla7g4mpv.css';
import '../../css/d/d4z8ksbxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="j7fmnlb4r"><path clip-rule="evenodd" class="tla7g4mpv"/><path class="d4z8ksbxz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:user-alt-6-line" {...props}></Icon>
