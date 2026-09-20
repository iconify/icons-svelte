<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2jc44cxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v2jc44cxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:text-start-a-sharp" {...props}></Icon>
