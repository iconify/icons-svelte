<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4er2kb1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f4er2kb1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:usb-flash-drive" {...props}></Icon>
