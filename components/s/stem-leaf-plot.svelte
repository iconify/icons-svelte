<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cr1sr0b5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cr1sr0b5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:stem-leaf-plot" {...props}></Icon>
