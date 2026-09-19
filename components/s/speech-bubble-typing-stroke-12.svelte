<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ow2_qqxpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ow2_qqxpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:speech-bubble-typing-stroke-12" {...props}></Icon>
