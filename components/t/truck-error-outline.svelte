<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byt-hfbpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="byt-hfbpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:truck-error-outline" {...props}></Icon>
