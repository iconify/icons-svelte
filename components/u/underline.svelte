<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5q6bm8so.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="g5q6bm8so"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:underline" {...props}></Icon>
