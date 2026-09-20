<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkdap9pwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wkdap9pwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:signal-tower-line" {...props}></Icon>
