<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwcwarblc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="hwcwarblc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:travel-airport-arrival-time-plane-airplane-trip-land-travel-time-adventure-timer-clock" {...props}></Icon>
