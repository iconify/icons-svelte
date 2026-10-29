<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/f/fgf5ofbsz.css';
import '../../css/p/pg2z7mb-s.css';
import '../../css/b/byz546bvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="fgf5ofbsz"/><path class="pg2z7mb-s wm-a"/><path class="byz546bvh wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:users-plus" {...props}></Icon>
