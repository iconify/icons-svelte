<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwm8xi_bv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vwm8xi_bv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:subway-alert-variant" {...props}></Icon>
