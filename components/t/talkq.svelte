<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rymd8jx_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rymd8jx_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:talkq" {...props}></Icon>
