<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqlq5clhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mqlq5clhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:solar-battery-5" {...props}></Icon>
