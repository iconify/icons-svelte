<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kaydvykfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kaydvykfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:weather-moonset" {...props}></Icon>
