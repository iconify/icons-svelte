<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4ebxdtqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d4ebxdtqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sideswipe" {...props}></Icon>
