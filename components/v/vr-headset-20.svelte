<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z15me-ble.css';
import '../../css/c/ctxclkbxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z15me-ble"/><path class="ctxclkbxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:vr-headset-20" {...props}></Icon>
