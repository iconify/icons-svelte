<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wws1cbc7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wws1cbc7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:speak-ai-line" {...props}></Icon>
