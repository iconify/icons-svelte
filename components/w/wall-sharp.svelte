<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjz98dbfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sjz98dbfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:wall-sharp" {...props}></Icon>
