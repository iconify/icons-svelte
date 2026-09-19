<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fp069p2og.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fp069p2og"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sugar-cane" {...props}></Icon>
