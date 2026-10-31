<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-tdchb9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z-tdchb9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:star-off-fill-round" {...props}></Icon>
