<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxyu0ybfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":512};
const content = `<path class="cxyu0ybfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:thermometer-empty" {...props}></Icon>
