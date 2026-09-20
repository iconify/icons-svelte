<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yixkk7odo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yixkk7odo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:smoothing-iron-outline" {...props}></Icon>
