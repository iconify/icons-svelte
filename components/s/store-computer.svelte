<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdqpnx-ip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="mdqpnx-ip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:store-computer" {...props}></Icon>
