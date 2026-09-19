<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ag9qn8bfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ag9qn8bfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tabletop-players" {...props}></Icon>
