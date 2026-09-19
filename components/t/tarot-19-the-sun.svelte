<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0sgzib0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p0sgzib0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tarot-19-the-sun" {...props}></Icon>
