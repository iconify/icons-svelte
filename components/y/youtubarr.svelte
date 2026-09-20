<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gq88usbhz.css';
import '../../css/i/i48zahbzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gq88usbhz"/><path class="i48zahbzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:youtubarr" {...props}></Icon>
