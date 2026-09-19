<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vic1rbbpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="vic1rbbpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:slideshow" {...props}></Icon>
