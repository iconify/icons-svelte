<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/paqsr5_ph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="paqsr5_ph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:video-player-slider-bold" {...props}></Icon>
