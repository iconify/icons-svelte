<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6oj308dp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d6oj308dp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:swipe-down-03" {...props}></Icon>
