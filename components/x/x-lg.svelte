<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhiwalbhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xhiwalbhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:x-lg" {...props}></Icon>
