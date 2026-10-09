<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbbf18bwz.css';
import '../../css/b/b_eke94bd.css';
import '../../css/p/p415zm30i.css';
import '../../css/p/pt38gvb4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rbbf18bwz"/><path class="b_eke94bd"/><path class="p415zm30i"/><path class="pt38gvb4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tidal-turbine-20" {...props}></Icon>
