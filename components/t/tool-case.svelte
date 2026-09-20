<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/huqpiok9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="huqpiok9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:tool-case" {...props}></Icon>
