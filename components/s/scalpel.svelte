<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ij2-9473u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ij2-9473u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:scalpel" {...props}></Icon>
