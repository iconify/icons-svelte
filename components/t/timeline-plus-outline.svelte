<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4q2c_9ec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l4q2c_9ec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:timeline-plus-outline" {...props}></Icon>
