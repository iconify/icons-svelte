<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_l0clr8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n_l0clr8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:weather-night-partly-cloudy" {...props}></Icon>
