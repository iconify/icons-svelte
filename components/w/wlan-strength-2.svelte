<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikpks56ft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ikpks56ft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:wlan-strength-2" {...props}></Icon>
