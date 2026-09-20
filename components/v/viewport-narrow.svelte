<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3k3fcbol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d3k3fcbol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:viewport-narrow" {...props}></Icon>
