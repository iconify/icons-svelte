<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zf1x_0b3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zf1x_0b3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:video-ai-line" {...props}></Icon>
