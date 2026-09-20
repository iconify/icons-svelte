<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsf4d8bxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rsf4d8bxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:webcam-video-off-remix" {...props}></Icon>
