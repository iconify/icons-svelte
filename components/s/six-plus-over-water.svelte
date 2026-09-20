<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i03w9cvef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="i03w9cvef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:six-plus-over-water" {...props}></Icon>
