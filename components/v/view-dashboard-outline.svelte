<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vv3b01bmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vv3b01bmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:view-dashboard-outline" {...props}></Icon>
