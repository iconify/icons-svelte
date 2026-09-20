<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsxf68bdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jsxf68bdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:wlan-strength-0" {...props}></Icon>
