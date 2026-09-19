<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tg8lbebsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tg8lbebsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:vibe" {...props}></Icon>
