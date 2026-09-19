<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mro3w3b6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mro3w3b6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:uncertainty" {...props}></Icon>
