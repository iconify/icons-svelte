<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/w/wxr4wwbgr.css';
import '../../css/u/unkvyfx-l.css';
import '../../css/e/e0izkne-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="wxr4wwbgr"/><path class="unkvyfx-l wm-s"/><path class="e0izkne-h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:unlink-duo" {...props}></Icon>
