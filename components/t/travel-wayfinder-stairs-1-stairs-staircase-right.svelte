<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aljnsoips.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="aljnsoips"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:travel-wayfinder-stairs-1-stairs-staircase-right" {...props}></Icon>
