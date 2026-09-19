<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3ta31sjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y3ta31sjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:star-filled" {...props}></Icon>
