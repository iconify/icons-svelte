<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7eb2bcam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s7eb2bcam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:video-player-fill" {...props}></Icon>
