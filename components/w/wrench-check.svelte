<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ps8-4yx3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ps8-4yx3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wrench-check" {...props}></Icon>
