<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjfd1vynk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mjfd1vynk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:usb" {...props}></Icon>
