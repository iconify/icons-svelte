<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry0q1bu3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ry0q1bu3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:zoom-out" {...props}></Icon>
