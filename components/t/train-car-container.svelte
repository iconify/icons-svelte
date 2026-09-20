<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqd5ycvcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pqd5ycvcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:train-car-container" {...props}></Icon>
