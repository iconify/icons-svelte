<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kecam2bme.css';
import '../../css/d/duw87ybvv.css';
import '../../css/z/zyyp67_ey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kecam2bme"/><path class="duw87ybvv"/><path class="zyyp67_ey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sprout-20-bold" {...props}></Icon>
