<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bweh7qb2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bweh7qb2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:spiked-wall" {...props}></Icon>
