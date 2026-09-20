<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdfcgjbiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hdfcgjbiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:webcam-cancelled-filled" {...props}></Icon>
