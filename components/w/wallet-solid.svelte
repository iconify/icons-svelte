<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrazanbrd.css';
import '../../css/k/k3m086bma.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 hrazanbrd"/><circle class="clr-i-solid clr-i-solid-path-2 k3m086bma"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:wallet-solid" {...props}></Icon>
