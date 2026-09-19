<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ply8xkbwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ply8xkbwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:trench-body-armor" {...props}></Icon>
