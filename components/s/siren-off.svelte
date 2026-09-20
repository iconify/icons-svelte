<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f81fp6svz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f81fp6svz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:siren-off" {...props}></Icon>
