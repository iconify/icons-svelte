<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rr7-mrbod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rr7-mrbod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:threat-usb-solid" {...props}></Icon>
