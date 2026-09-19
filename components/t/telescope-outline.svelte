<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oy3iztbmk.css';
import '../../css/s/sulj6_b9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oy3iztbmk"/><path class="sulj6_b9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:telescope-outline" {...props}></Icon>
