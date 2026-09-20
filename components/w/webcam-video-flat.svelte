<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2_2mi01k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="o2_2mi01k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:webcam-video-flat" {...props}></Icon>
