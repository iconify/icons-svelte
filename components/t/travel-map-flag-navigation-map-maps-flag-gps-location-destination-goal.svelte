<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqgpm_b_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="uqgpm_b_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:travel-map-flag-navigation-map-maps-flag-gps-location-destination-goal" {...props}></Icon>
