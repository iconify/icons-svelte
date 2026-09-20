<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c14c-h18e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c14c-h18e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:sliders-vertical" {...props}></Icon>
