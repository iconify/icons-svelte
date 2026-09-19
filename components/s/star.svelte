<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_x5ixsem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d_x5ixsem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:star" {...props}></Icon>
