<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbh-7tfuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xbh-7tfuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:video-off-line" {...props}></Icon>
