<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/z/zog9gac6u.css';
import '../../css/i/ihlcnwbup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="y9tr6bcfx"><path class="zog9gac6u"/><circle class="ihlcnwbup"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:travel-map-location-pin-navigation-map-maps-pin-gps-location" {...props}></Icon>
