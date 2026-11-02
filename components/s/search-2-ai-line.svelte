<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvjty8bgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xvjty8bgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:search-2-ai-line" {...props}></Icon>
