<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/df3f3o36e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="df3f3o36e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:video-camera-1-filled" {...props}></Icon>
