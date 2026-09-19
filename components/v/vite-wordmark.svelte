<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6x4u0bao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="g6x4u0bao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:vite-wordmark" {...props}></Icon>
