<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l58-tfryc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l58-tfryc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:spade-skull" {...props}></Icon>
