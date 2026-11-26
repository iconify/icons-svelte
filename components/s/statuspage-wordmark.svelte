<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dr24xacoy.css';
import '../../css/e/etdr-zbkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="dr24xacoy"/><path class="etdr-zbkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:statuspage-wordmark" {...props}></Icon>
