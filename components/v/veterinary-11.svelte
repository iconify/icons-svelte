<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yd4l3abhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="yd4l3abhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:veterinary-11" {...props}></Icon>
