<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/widswmrqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="widswmrqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:spiral-shape" {...props}></Icon>
