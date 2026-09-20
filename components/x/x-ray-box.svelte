<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpknzmbqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zpknzmbqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:x-ray-box" {...props}></Icon>
