<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dq946zbdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dq946zbdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:weather-windy-variant" {...props}></Icon>
