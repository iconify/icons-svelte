<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gz1pg6brd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gz1pg6brd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:wooden-pegleg" {...props}></Icon>
