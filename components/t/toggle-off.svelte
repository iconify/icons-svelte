<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vws3t-8ts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":1280};
const content = `<path class="vws3t-8ts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:toggle-off" {...props}></Icon>
