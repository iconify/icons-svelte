<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srq6p5b9s.css';
import '../../css/g/gxp1ob29q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="srq6p5b9s"/><path class="gxp1ob29q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:tn-1x1" {...props}></Icon>
