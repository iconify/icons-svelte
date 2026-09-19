<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d40i0wfdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d40i0wfdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:satellite-communication" {...props}></Icon>
