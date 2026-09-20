<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-s4cclro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="s-s4cclro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:water-pipe-return-bend-with-motor-and-handle" {...props}></Icon>
