<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/og5zj6tba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="og5zj6tba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:rounded-square-with-dot" {...props}></Icon>
