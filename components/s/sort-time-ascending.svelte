<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vy5mv509z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vy5mv509z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sort-time-ascending" {...props}></Icon>
