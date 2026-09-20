<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9wvuq-ij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l9wvuq-ij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:weather-cloudy" {...props}></Icon>
