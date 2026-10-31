<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zg5o3i7gs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zg5o3i7gs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:tabletop-microphone-under-gabled-roof" {...props}></Icon>
