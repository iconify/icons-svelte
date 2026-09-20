<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlqfyf96a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dlqfyf96a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:screen-rotation" {...props}></Icon>
