<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-5v3uhca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r-5v3uhca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sign-direction" {...props}></Icon>
