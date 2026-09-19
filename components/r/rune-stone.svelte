<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pli1b6bwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pli1b6bwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:rune-stone" {...props}></Icon>
