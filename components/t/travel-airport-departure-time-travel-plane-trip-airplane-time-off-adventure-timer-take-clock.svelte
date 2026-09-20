<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgrhv-byx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="mgrhv-byx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:travel-airport-departure-time-travel-plane-trip-airplane-time-off-adventure-timer-take-clock" {...props}></Icon>
