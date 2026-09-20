<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uu4gmzb1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="uu4gmzb1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:suitcase-in-rectangle-outline-and-key" {...props}></Icon>
