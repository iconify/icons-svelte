<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0pvjobkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c0pvjobkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:send-sqaure-filled" {...props}></Icon>
