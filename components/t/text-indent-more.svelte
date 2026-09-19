<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tui3x3bgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tui3x3bgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:text-indent-more" {...props}></Icon>
