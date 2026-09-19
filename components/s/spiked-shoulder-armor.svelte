<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rv1-spb_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rv1-spb_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:spiked-shoulder-armor" {...props}></Icon>
