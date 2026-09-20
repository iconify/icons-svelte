<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbkmpjbyx.css';
import '../../css/a/ag9gbdcug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vbkmpjbyx"/><path class="ag9gbdcug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:video-camera-line" {...props}></Icon>
