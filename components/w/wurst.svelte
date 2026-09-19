<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wo-wl5pgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wo-wl5pgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:wurst" {...props}></Icon>
