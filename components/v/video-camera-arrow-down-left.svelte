<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zx6ys8baq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zx6ys8baq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:video-camera-arrow-down-left" {...props}></Icon>
