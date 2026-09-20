<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhctsdbai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xhctsdbai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:usb-port-solid" {...props}></Icon>
