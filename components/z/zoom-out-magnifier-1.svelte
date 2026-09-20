<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q41sffd_i.css';
import '../../css/p/pmn3hkbsz.css';
import '../../css/y/yd340rbvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q41sffd_i"/><path class="pmn3hkbsz"/><path class="yd340rbvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:zoom-out-magnifier-1" {...props}></Icon>
