<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w404mpg1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="w404mpg1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:video-camera-filled" {...props}></Icon>
