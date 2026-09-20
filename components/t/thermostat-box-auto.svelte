<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imxzj81sz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="imxzj81sz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:thermostat-box-auto" {...props}></Icon>
