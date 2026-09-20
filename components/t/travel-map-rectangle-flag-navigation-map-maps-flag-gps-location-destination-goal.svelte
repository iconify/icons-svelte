<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rk2cr0b6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="rk2cr0b6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:travel-map-rectangle-flag-navigation-map-maps-flag-gps-location-destination-goal" {...props}></Icon>
