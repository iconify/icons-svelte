<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0_g-seyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p0_g-seyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:z-axis" {...props}></Icon>
