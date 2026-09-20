<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp8fpmbyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xp8fpmbyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:terminal-ai-fill" {...props}></Icon>
