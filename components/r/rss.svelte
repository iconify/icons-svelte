<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4ug2vk3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w4ug2vk3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:rss" {...props}></Icon>
