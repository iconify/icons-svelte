<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfz9ytbhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tfz9ytbhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:square-chevron-right-sharp" {...props}></Icon>
