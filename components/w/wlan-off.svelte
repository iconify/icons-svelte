<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shhu5beuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="shhu5beuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:wlan-off" {...props}></Icon>
