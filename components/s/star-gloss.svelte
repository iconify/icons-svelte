<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yb8h83o9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yb8h83o9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:star-gloss" {...props}></Icon>
