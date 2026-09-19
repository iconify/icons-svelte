<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3643wbba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n3643wbba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:spear-hook" {...props}></Icon>
