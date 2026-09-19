<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d98-p5wvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d98-p5wvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:teleport" {...props}></Icon>
