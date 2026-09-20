<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqsf4l63w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hqsf4l63w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:water" {...props}></Icon>
