<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cg_2tebxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cg_2tebxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:spiked-armor" {...props}></Icon>
