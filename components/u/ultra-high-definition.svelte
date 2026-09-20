<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcv2l6t1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rcv2l6t1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ultra-high-definition" {...props}></Icon>
