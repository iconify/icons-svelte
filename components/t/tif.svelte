<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z02o_h7tc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z02o_h7tc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:tif" {...props}></Icon>
