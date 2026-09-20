<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxf6sztqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sxf6sztqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:taichigraphics" {...props}></Icon>
