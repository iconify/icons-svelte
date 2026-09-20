<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/im1uwjbaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="im1uwjbaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:trending-down" {...props}></Icon>
