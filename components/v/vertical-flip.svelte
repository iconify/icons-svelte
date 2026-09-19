<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dp210-bgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dp210-bgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:vertical-flip" {...props}></Icon>
