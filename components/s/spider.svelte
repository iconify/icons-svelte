<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/n/nn2f9gisi.css';
import '../../css/d/dk-3u6b9m.css';
import '../../css/g/gcej-6bbf.css';
import '../../css/p/p3dq04btg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="nn2f9gisi"/><path class="dk-3u6b9m"/><path class="gcej-6bbf wm-a"/><path class="p3dq04btg wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:spider" {...props}></Icon>
