<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/razlacc1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="razlacc1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:wlan-strength-1-lock" {...props}></Icon>
