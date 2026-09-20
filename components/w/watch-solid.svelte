<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjlvsp_ed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jjlvsp_ed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:watch-solid" {...props}></Icon>
