<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whkzpac3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="whkzpac3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:signature-2-ai-line" {...props}></Icon>
