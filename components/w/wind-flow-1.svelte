<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otcmcwblu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="otcmcwblu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:wind-flow-1" {...props}></Icon>
