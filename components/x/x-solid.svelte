<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbr2rikas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tbr2rikas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:x-solid" {...props}></Icon>
