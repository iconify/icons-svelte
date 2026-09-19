<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5w_fg8wp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x5w_fg8wp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:shoulder-armor" {...props}></Icon>
