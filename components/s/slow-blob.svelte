<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpfd2sbjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dpfd2sbjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:slow-blob" {...props}></Icon>
