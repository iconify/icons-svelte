<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2tf6pbhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":304,"height":464};
const content = `<path class="t2tf6pbhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:usb" {...props}></Icon>
