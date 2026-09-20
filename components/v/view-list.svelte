<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7f13onla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r7f13onla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:view-list" {...props}></Icon>
