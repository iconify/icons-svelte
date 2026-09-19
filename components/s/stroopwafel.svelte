<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/znxl5ob6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="znxl5ob6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:stroopwafel" {...props}></Icon>
