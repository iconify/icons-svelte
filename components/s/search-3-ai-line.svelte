<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ua000itue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ua000itue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:search-3-ai-line" {...props}></Icon>
