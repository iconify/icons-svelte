<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slrd-751e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="slrd-751e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:swipe-card" {...props}></Icon>
