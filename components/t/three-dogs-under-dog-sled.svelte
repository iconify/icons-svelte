<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rx5z0ablq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rx5z0ablq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:three-dogs-under-dog-sled" {...props}></Icon>
