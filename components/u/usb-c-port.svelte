<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/leceepm3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="leceepm3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:usb-c-port" {...props}></Icon>
