<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msjkc3bsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="msjkc3bsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:scratch-map-dark" {...props}></Icon>
