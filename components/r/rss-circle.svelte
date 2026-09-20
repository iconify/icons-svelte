<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hs66k5bto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hs66k5bto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:rss-circle" {...props}></Icon>
