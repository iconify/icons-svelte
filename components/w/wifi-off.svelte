<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hk14dmbbe.css';
import '../../css/k/km46x-8as.css';
import '../../css/f/fov68487d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hk14dmbbe"/><circle class="km46x-8as"/><path class="fov68487d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:wifi-off" {...props}></Icon>
