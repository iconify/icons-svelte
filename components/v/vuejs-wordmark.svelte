<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w12d0osrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="w12d0osrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:vuejs-wordmark" {...props}></Icon>
