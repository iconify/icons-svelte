<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mslrnwbgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mslrnwbgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:star-half-solid" {...props}></Icon>
