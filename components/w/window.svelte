<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpdcp2piy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vpdcp2piy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:window" {...props}></Icon>
