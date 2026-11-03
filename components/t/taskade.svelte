<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vh4z5kbri.css';
import '../../css/v/vhk8n-b7m.css';
import '../../css/h/hlbcq7bvh.css';
import '../../css/p/pdlb79bnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="vh4z5kbri"/><circle class="vhk8n-b7m"/><path class="hlbcq7bvh"/><path class="pdlb79bnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:taskade" {...props}></Icon>
