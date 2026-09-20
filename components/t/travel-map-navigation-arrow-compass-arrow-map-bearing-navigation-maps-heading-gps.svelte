<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pebb46n6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="pebb46n6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:travel-map-navigation-arrow-compass-arrow-map-bearing-navigation-maps-heading-gps" {...props}></Icon>
