<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6d33_q5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d6d33_q5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tarot-10-wheel-of-fortune" {...props}></Icon>
