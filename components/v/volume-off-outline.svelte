<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgz03y5cu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mgz03y5cu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:volume-off-outline" {...props}></Icon>
