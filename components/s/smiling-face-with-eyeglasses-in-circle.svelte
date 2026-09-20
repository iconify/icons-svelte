<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yuuh15blj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yuuh15blj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:smiling-face-with-eyeglasses-in-circle" {...props}></Icon>
