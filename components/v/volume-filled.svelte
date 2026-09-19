<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnd-sxdgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xnd-sxdgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:volume-filled" {...props}></Icon>
