<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzjpy33mt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mzjpy33mt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:water-standpipe-with-pump-handle-and-droplet" {...props}></Icon>
