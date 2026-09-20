<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ip-lx2qei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ip-lx2qei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:vector-polyline" {...props}></Icon>
