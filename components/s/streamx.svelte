<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/np-sskbor.css';
import '../../css/j/jsr-a6v3g.css';
import '../../css/t/t-sci2y1e.css';
import '../../css/y/y0c2lnwwu.css';
import '../../css/m/mrqxd1bkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="np-sskbor"/><path class="jsr-a6v3g"/><path class="t-sci2y1e"/><path class="y0c2lnwwu"/><path class="mrqxd1bkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:streamx" {...props}></Icon>
