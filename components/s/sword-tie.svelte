<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1d3tpb0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j1d3tpb0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sword-tie" {...props}></Icon>
