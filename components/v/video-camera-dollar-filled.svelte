<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn6igabhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hn6igabhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:video-camera-dollar-filled" {...props}></Icon>
