<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvy7v3bvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uvy7v3bvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tank" {...props}></Icon>
