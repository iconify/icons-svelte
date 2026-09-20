<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_goq96ao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="d_goq96ao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:sea-star-under-water" {...props}></Icon>
