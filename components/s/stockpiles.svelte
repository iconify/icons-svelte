<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ew93jbbuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ew93jbbuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:stockpiles" {...props}></Icon>
