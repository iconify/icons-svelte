<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvsuz0qrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zvsuz0qrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:star" {...props}></Icon>
