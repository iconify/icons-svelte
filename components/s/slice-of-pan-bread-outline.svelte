<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1uavwwpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="v1uavwwpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:slice-of-pan-bread-outline" {...props}></Icon>
