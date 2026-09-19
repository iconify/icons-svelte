<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1h3fgbee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u1h3fgbee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:shiny-entrance" {...props}></Icon>
