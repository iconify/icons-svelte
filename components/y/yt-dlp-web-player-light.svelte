<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnaz4ljev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lnaz4ljev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yt-dlp-web-player-light" {...props}></Icon>
