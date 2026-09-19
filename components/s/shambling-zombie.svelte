<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhzql1b2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jhzql1b2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:shambling-zombie" {...props}></Icon>
