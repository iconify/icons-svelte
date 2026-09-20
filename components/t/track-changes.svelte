<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnai3j2qk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gnai3j2qk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:track-changes" {...props}></Icon>
