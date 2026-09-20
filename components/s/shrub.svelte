<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8udzeb7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="l8udzeb7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:shrub" {...props}></Icon>
