<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yr_9c2bvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yr_9c2bvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:vinyl" {...props}></Icon>
