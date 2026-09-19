<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lysg5zyhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lysg5zyhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:view-sidebar-left" {...props}></Icon>
