<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyr36-bkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vyr36-bkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:sunglasses" {...props}></Icon>
