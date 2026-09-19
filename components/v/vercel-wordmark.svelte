<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1k2tmaip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="g1k2tmaip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:vercel-wordmark" {...props}></Icon>
