<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fssh11-nv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fssh11-nv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:speed-slow" {...props}></Icon>
