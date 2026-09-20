<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knpoae5ge.css';
import '../../css/i/ipyektf-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="knpoae5ge"/><path class="ipyektf-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yt-dlp-web-player" {...props}></Icon>
