<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dykt1tozj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dykt1tozj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:usb" {...props}></Icon>
