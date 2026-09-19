<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/ba9j2hbqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ba9j2hbqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:screen-rotation" {...props}></Icon>
