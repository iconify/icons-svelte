<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8m-vw4_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p8m-vw4_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:siege-ram" {...props}></Icon>
