<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwrbt_kpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nwrbt_kpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:water-splash" {...props}></Icon>
