<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbtz19omd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="lbtz19omd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:webcam-video-remix" {...props}></Icon>
