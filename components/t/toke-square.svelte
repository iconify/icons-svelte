<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ruvov2dhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ruvov2dhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:toke-square" {...props}></Icon>
