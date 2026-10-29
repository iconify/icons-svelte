<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/max9occ2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="max9occ2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:usb-solid" {...props}></Icon>
