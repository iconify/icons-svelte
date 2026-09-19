<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcczfikza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mcczfikza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sword-break" {...props}></Icon>
