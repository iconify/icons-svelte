<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2t1a2bpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="h2t1a2bpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:webcam-video-circle-remix" {...props}></Icon>
