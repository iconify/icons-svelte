<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxb4accij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sxb4accij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:shambling-mound" {...props}></Icon>
