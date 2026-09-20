<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vs38770rt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vs38770rt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:weather-sunny" {...props}></Icon>
