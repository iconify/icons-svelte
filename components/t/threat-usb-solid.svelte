<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/stxl60b4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="stxl60b4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:threat-usb-solid" {...props}></Icon>
