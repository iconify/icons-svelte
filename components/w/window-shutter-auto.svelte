<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1hp5lcav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j1hp5lcav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:window-shutter-auto" {...props}></Icon>
