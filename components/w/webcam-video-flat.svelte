<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smmnezbxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="smmnezbxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:webcam-video-flat" {...props}></Icon>
