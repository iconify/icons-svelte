<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acddq37ag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="acddq37ag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yt-dlp-web-player-dark" {...props}></Icon>
