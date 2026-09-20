<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jb_gs7z-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jb_gs7z-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:volume-2" {...props}></Icon>
