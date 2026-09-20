<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvqi0ubzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cvqi0ubzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:usb-solid" {...props}></Icon>
