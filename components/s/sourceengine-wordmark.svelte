<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glb07y6od.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="glb07y6od"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:sourceengine-wordmark" {...props}></Icon>
