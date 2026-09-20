<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsc84_2my.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lsc84_2my"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:square-scissors-sharp" {...props}></Icon>
