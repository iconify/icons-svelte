<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iin6sj8pc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="iin6sj8pc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:webcam-video-off-remix" {...props}></Icon>
