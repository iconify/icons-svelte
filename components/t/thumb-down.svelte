<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pf203d6op.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pf203d6op"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:thumb-down" {...props}></Icon>
