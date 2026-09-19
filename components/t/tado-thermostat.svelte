<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygudqqb2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ygudqqb2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:tado-thermostat" {...props}></Icon>
