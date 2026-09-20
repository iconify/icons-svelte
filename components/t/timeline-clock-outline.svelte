<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5bns_y0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p5bns_y0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:timeline-clock-outline" {...props}></Icon>
