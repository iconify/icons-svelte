<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xk8qblmxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xk8qblmxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:wall-hanging-with-mountains-and-sun" {...props}></Icon>
