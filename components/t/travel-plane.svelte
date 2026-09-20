<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie7ohsbhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ie7ohsbhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:travel-plane" {...props}></Icon>
