<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmgvc-bss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wmgvc-bss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:vibe-coding-fill" {...props}></Icon>
