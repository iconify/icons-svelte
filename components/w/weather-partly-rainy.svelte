<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yz-9f0blo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yz-9f0blo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:weather-partly-rainy" {...props}></Icon>
