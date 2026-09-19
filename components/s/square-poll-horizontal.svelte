<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7pdt0-gz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="g7pdt0-gz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:square-poll-horizontal" {...props}></Icon>
