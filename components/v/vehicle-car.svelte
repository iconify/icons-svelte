<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vj84xyb2g.css';
import '../../css/z/zeoxv5b2o.css';
import '../../css/p/pmgt1fc3u.css';
import '../../css/j/j6u3e6b3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vj84xyb2g"/><circle class="zeoxv5b2o"/><circle class="pmgt1fc3u"/><path class="j6u3e6b3n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:vehicle-car" {...props}></Icon>
