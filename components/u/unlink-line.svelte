<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zb0pgvzvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zb0pgvzvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:unlink-line" {...props}></Icon>
