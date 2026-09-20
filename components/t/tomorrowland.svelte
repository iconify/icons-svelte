<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xg5vk18uq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xg5vk18uq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:tomorrowland" {...props}></Icon>
