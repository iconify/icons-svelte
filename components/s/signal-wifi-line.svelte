<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhnh0nrcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mhnh0nrcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:signal-wifi-line" {...props}></Icon>
