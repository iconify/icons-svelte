<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yotfb98wq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yotfb98wq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:shirt" {...props}></Icon>
