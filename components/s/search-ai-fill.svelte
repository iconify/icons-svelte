<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1bveobjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j1bveobjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:search-ai-fill" {...props}></Icon>
