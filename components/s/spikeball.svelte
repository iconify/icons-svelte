<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frip6ub2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="frip6ub2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:spikeball" {...props}></Icon>
