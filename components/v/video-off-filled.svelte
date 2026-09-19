<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iktrg_pfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="iktrg_pfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:video-off-filled" {...props}></Icon>
