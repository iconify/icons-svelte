<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rp0nxibaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="rp0nxibaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:swipe-map-v" {...props}></Icon>
