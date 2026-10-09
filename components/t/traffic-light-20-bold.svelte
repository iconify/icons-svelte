<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/og5fw-c9e.css';
import '../../css/b/b16yxabjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="og5fw-c9e"/><path class="b16yxabjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:traffic-light-20-bold" {...props}></Icon>
