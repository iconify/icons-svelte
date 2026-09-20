<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsrfxxbcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bsrfxxbcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:weather-cloudy-arrow-right" {...props}></Icon>
