<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgws2bbph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vgws2bbph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:video-camera-off" {...props}></Icon>
