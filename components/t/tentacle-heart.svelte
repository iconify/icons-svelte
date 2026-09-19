<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hc6br1bwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hc6br1bwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tentacle-heart" {...props}></Icon>
