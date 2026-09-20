<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbu43julu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zbu43julu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sort-descending" {...props}></Icon>
