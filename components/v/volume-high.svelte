<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrxs8yb0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="rrxs8yb0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:volume-high" {...props}></Icon>
