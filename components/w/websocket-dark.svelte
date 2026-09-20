<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3l2wxb4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m3l2wxb4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:websocket-dark" {...props}></Icon>
