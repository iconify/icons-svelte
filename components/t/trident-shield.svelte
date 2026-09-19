<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xm64734gg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xm64734gg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:trident-shield" {...props}></Icon>
