<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xx1qjcbmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xx1qjcbmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:star-flag" {...props}></Icon>
