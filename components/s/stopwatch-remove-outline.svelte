<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2e0i2d_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p2e0i2d_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:stopwatch-remove-outline" {...props}></Icon>
