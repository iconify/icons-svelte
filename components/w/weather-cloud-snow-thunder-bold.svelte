<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vft_ecclt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vft_ecclt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:weather-cloud-snow-thunder-bold" {...props}></Icon>
