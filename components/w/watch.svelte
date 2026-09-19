<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2x4u1b7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":512};
const content = `<path class="l2x4u1b7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:watch" {...props}></Icon>
