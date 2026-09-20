<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e56w4s-6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="e56w4s-6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:spray-can" {...props}></Icon>
