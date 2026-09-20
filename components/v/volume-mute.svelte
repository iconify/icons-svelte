<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4l225b0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u4l225b0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:volume-mute" {...props}></Icon>
