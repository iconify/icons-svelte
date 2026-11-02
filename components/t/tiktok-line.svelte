<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gptlxqbin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gptlxqbin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tiktok-line" {...props}></Icon>
