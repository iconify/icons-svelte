<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/up8o3o55e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="up8o3o55e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:vomiting-outline-24px" {...props}></Icon>
