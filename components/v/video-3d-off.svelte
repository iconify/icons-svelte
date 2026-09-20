<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmtyaabri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fmtyaabri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:video-3d-off" {...props}></Icon>
