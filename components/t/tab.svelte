<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcuc76lyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dcuc76lyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:tab" {...props}></Icon>
