<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/win80zbcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="win80zbcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sand-castle" {...props}></Icon>
