<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mslm4062n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mslm4062n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:semicircle-solid" {...props}></Icon>
