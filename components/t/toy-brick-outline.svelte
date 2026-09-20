<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7hjfyuio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d7hjfyuio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:toy-brick-outline" {...props}></Icon>
