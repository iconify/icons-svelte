<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rawlm3oon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="rawlm3oon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:star-half" {...props}></Icon>
