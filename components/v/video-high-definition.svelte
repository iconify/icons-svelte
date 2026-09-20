<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8_u2ackk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y8_u2ackk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:video-high-definition" {...props}></Icon>
