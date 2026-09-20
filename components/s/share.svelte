<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cy52vvbrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cy52vvbrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:share" {...props}></Icon>
