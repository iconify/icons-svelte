<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8_xspb3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="t8_xspb3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:video-camera" {...props}></Icon>
