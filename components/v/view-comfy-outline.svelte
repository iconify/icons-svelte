<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2js0bcam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g2js0bcam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:view-comfy-outline" {...props}></Icon>
