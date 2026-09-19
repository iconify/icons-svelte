<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dr_g1b63o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="dr_g1b63o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:speech-bubble-plain-stroke-12" {...props}></Icon>
