<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y57xxsbbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y57xxsbbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:video-off-stroke-16" {...props}></Icon>
