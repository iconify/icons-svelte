<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyrz0touf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xyrz0touf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:video-box" {...props}></Icon>
