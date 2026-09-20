<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfhd0ccqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":356,"height":400,"top":-15};
const content = `<path class="colorff4500 svgShape yfhd0ccqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:vedic" {...props}></Icon>
