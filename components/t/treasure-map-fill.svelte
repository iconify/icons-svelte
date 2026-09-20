<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgnzx4bri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fgnzx4bri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:treasure-map-fill" {...props}></Icon>
