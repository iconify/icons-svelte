<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zp6ggp7mt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zp6ggp7mt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:student" {...props}></Icon>
