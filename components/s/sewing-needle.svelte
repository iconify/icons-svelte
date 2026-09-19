<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtg_m-bgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mtg_m-bgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sewing-needle" {...props}></Icon>
