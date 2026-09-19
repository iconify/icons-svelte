<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xj2mv2b3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xj2mv2b3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:water-recycling" {...props}></Icon>
