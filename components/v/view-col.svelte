<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdg_7jb_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xdg_7jb_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:view-col" {...props}></Icon>
