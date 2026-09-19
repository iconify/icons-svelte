<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1yx-1y0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="c1yx-1y0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:xmark-circle" {...props}></Icon>
