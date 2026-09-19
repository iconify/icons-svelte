<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hshx60-si.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="hshx60-si"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:webgpu-wordmark" {...props}></Icon>
