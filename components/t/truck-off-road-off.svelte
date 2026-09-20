<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xg06_ub1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xg06_ub1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:truck-off-road-off" {...props}></Icon>
