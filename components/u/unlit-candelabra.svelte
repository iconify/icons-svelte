<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynxt2hu3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ynxt2hu3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:unlit-candelabra" {...props}></Icon>
