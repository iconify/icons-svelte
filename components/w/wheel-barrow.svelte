<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zq2i94jsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zq2i94jsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wheel-barrow" {...props}></Icon>
