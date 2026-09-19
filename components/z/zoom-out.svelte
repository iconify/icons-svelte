<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di6q9o7nh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="di6q9o7nh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:zoom-out" {...props}></Icon>
