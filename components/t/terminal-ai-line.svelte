<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5drg8byv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l5drg8byv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:terminal-ai-line" {...props}></Icon>
