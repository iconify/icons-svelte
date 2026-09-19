<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5zn4-brr.css';
import '../../css/z/zxlwz1bsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b5zn4-brr"/><path class="zxlwz1bsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:text-mining" {...props}></Icon>
