<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rm7z24m1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rm7z24m1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:truck" {...props}></Icon>
