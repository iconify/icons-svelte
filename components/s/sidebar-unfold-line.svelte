<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eh7qx1bct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eh7qx1bct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:sidebar-unfold-line" {...props}></Icon>
