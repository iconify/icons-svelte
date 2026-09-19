<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft7_ypb2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":416,"height":480};
const content = `<path class="ft7_ypb2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:timer-off" {...props}></Icon>
