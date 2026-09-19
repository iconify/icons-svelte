<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlbdts9qu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rlbdts9qu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:wind-hole" {...props}></Icon>
