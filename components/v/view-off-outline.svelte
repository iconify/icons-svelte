<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9p5z8bbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h9p5z8bbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:view-off-outline" {...props}></Icon>
