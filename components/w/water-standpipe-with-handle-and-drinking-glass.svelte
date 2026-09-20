<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcosmutfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rcosmutfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:water-standpipe-with-handle-and-drinking-glass" {...props}></Icon>
