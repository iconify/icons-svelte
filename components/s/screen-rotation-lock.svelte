<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2c5etzdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":488,"height":496};
const content = `<path class="t2c5etzdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:screen-rotation-lock" {...props}></Icon>
