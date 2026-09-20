<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfkh_9xxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bfkh_9xxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:vlc-media-player" {...props}></Icon>
