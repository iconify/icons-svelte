<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9qs8hiyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l9qs8hiyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:weather-cloudy-alert" {...props}></Icon>
