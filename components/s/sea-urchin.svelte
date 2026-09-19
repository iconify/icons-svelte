<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nh4s1z2xe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nh4s1z2xe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sea-urchin" {...props}></Icon>
