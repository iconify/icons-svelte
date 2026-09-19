<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p08cwsb5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p08cwsb5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:striking-splinter" {...props}></Icon>
