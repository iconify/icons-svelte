<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/llx19_bqv.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/s/sxdp1lo8c.css';
import '../../css/a/a74c774yq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="llx19_bqv"/><g class="ij2x_72vy"><path class="sxdp1lo8c"/><path class="a74c774yq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:spider-web" {...props}></Icon>
