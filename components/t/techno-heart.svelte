<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wb4t3pbgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wb4t3pbgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:techno-heart" {...props}></Icon>
