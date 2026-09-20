<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dr_vc52xd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dr_vc52xd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:television-off" {...props}></Icon>
