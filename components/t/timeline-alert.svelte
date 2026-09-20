<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxek1-9tk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bxek1-9tk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:timeline-alert" {...props}></Icon>
