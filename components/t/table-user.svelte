<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xps3pd9pj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xps3pd9pj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:table-user" {...props}></Icon>
