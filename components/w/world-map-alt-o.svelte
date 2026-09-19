<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ld3-dq87l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="ld3-dq87l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:world-map-alt-o" {...props}></Icon>
