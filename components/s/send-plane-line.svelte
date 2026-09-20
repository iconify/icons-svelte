<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqix3_b1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hqix3_b1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:send-plane-line" {...props}></Icon>
