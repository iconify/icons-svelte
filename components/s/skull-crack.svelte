<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm_heiskl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dm_heiskl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:skull-crack" {...props}></Icon>
