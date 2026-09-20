<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1fyd2gnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="j1fyd2gnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:two-tall-rectangles-top-left" {...props}></Icon>
