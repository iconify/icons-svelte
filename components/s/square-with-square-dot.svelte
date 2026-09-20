<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/un5t715gt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="un5t715gt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:square-with-square-dot" {...props}></Icon>
