<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/io5j2zbie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="io5j2zbie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:webrtc" {...props}></Icon>
