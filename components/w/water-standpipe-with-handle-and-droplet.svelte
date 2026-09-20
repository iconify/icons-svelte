<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npbprc1fp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="npbprc1fp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:water-standpipe-with-handle-and-droplet" {...props}></Icon>
