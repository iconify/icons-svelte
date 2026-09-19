<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihikl0b1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ihikl0b1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ubisoft-sun" {...props}></Icon>
