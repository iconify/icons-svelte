<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/em-2je60d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="em-2je60d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:volume-x-solid" {...props}></Icon>
