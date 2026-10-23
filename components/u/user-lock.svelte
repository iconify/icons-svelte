<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgig8kbiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pgig8kbiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:user-lock" {...props}></Icon>
