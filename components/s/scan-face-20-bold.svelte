<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3dl8_bpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e3dl8_bpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:scan-face-20-bold" {...props}></Icon>
