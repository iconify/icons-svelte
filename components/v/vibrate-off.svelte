<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yk7c11bxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yk7c11bxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:vibrate-off" {...props}></Icon>
