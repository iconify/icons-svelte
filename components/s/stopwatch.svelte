<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw-b0c38h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rw-b0c38h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:stopwatch" {...props}></Icon>
