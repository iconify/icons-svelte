<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8vd6_b3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="r8vd6_b3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:treasure-map" {...props}></Icon>
