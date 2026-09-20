<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zijm3bbic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zijm3bbic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:uptime-monitor-dark" {...props}></Icon>
