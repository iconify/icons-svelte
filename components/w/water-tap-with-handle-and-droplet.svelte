<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jc77nee5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jc77nee5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:water-tap-with-handle-and-droplet" {...props}></Icon>
