<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zs-a7_bqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zs-a7_bqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:uptime-monitor-light" {...props}></Icon>
