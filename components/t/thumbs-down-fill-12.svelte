<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/glcp_kbvh.css';
import '../../css/v/vumopju_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<g class="cuyn6tgcc"><path class="glcp_kbvh"/><rect class="vumopju_m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:thumbs-down-fill-12" {...props}></Icon>
