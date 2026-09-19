<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iy5cukbng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iy5cukbng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:torc" {...props}></Icon>
