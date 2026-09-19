<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-ysc-d4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y-ysc-d4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:traffic-cone" {...props}></Icon>
