<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nojv07bhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nojv07bhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:usb-port-solid" {...props}></Icon>
