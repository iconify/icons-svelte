<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4efcp-nh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j4efcp-nh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:timer-pause" {...props}></Icon>
