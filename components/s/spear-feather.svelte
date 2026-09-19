<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0ik8bcyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y0ik8bcyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:spear-feather" {...props}></Icon>
