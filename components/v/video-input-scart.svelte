<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpzw5abdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fpzw5abdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:video-input-scart" {...props}></Icon>
