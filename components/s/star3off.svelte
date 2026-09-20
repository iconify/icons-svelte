<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zth73zbcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zth73zbcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:star3off" {...props}></Icon>
