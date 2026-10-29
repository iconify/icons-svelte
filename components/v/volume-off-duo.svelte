<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/k459z7k3d.css';
import '../../css/d/d074ckbgd.css';
import '../../css/s/st-oxhb_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="k459z7k3d"/><path class="d074ckbgd wm-s"/><path class="st-oxhb_e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:volume-off-duo" {...props}></Icon>
