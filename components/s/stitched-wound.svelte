<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_g_d8bvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d_g_d8bvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:stitched-wound" {...props}></Icon>
