<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3xfu_bwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e3xfu_bwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:tablet-sharp" {...props}></Icon>
