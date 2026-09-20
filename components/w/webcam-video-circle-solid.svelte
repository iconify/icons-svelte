<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcij4pbge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lcij4pbge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:webcam-video-circle-solid" {...props}></Icon>
