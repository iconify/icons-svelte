<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iq-mk8b4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="iq-mk8b4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:tanstack-wordmark" {...props}></Icon>
