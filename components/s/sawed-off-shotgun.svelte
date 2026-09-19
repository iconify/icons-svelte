<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isonwbcyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="isonwbcyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sawed-off-shotgun" {...props}></Icon>
