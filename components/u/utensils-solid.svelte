<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmr23pb1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cmr23pb1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:utensils-solid" {...props}></Icon>
