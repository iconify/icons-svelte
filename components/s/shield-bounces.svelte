<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jl1w99b7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jl1w99b7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:shield-bounces" {...props}></Icon>
