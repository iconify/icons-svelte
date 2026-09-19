<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5mkn8bzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w5mkn8bzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:time-synchronization" {...props}></Icon>
