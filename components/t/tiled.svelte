<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_q78v67e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b_q78v67e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:tiled" {...props}></Icon>
