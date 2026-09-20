<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/su2h7db8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="su2h7db8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:webcam-off" {...props}></Icon>
