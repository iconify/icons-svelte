<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsb9exiyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rsb9exiyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:text-add" {...props}></Icon>
