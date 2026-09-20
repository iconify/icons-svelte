<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aux66vpig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aux66vpig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shop-clock-outline" {...props}></Icon>
