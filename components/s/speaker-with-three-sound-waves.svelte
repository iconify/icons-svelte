<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ih80zmben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ih80zmben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:speaker-with-three-sound-waves" {...props}></Icon>
