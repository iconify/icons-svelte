<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpeag11mw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wpeag11mw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:video-camera-2-line" {...props}></Icon>
