<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odn7d_b4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="odn7d_b4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:text-cursor-input-sharp" {...props}></Icon>
