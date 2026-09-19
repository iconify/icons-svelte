<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbvq_ebvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fbvq_ebvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:shuffle" {...props}></Icon>
