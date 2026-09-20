<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgd7_gbom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cgd7_gbom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wifi-strength-off" {...props}></Icon>
