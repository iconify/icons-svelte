<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkqkbp-3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="rkqkbp-3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:travel-map-navigation-arrow-off-compass-arrow-map-bearing-navigation-maps-heading-gps-off-disable" {...props}></Icon>
