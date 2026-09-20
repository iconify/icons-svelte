<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upw6qkbvk.css';
import '../../css/x/x1mdp195q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="upw6qkbvk"/><path class="x1mdp195q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:yellow-hexagon" {...props}></Icon>
