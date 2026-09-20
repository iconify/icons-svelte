<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mphmn5bad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mphmn5bad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:text-account" {...props}></Icon>
