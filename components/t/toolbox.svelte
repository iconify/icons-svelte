<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2kvgvbvc.css';
import '../../css/d/d9lq-0bsu.css';
import '../../css/s/spa5w1b_u.css';
import '../../css/b/b3fp9-wfe.css';
import '../../css/p/pj47wlbgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="d9lq-0bsu"/><path class="spa5w1b_u"/><path class="b3fp9-wfe"/><path class="pj47wlbgr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:toolbox" {...props}></Icon>
