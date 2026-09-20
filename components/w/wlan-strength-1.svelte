<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2qtytb1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b2qtytb1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:wlan-strength-1" {...props}></Icon>
