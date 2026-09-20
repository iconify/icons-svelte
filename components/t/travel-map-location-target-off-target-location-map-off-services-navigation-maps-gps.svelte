<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xq18cp_ys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="xq18cp_ys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:travel-map-location-target-off-target-location-map-off-services-navigation-maps-gps" {...props}></Icon>
