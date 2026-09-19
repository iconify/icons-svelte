<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5vgbcb_s.css';
import '../../css/v/vmyfv_bvg.css';
import '../../css/w/wgqpd53tm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<path class="y5vgbcb_s"/><path class="vmyfv_bvg"/><path class="wgqpd53tm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:wf-4x3" {...props}></Icon>
