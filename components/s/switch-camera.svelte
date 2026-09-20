<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gub3n7bnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gub3n7bnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:switch-camera" {...props}></Icon>
