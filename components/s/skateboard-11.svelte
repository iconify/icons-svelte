<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-4_k_y0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="r-4_k_y0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:skateboard-11" {...props}></Icon>
