<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fcr65cb0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fcr65cb0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:thumb-down-outline" {...props}></Icon>
