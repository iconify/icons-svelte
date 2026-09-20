<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgbn20iyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wgbn20iyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wifi-strength-lock-open-outline" {...props}></Icon>
