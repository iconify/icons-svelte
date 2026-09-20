<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/llky-5b5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="llky-5b5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:watch-sharp" {...props}></Icon>
