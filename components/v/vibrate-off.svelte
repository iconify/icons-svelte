<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-hb8rb1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-hb8rb1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:vibrate-off" {...props}></Icon>
