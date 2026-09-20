<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/weypos4si.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="weypos4si"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:triangular-pill-and-circular-pill-and-capsule-pill" {...props}></Icon>
