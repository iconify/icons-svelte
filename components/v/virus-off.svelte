<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qg45pac-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qg45pac-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:virus-off" {...props}></Icon>
